# Drupal कंसोल स्थापनाकर्ता का उपयोग करते हुए
आप अपनी परियोजना निर्देशिका में संस्थापक को चलाने के द्वारा स्थानीय रूप से Drupal कंसोल को स्थापित कर सकते हैं, संस्थापक आपको कंप्यूटर पर Drupal कंसोल चलाने के लिए आवश्यक फ़ाइलों को डाउनलोड करने का ख्याल कंसोल|

## curl का उपयोग करते हुए:
```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
```
## अगर आप के पास curl नही है तो:
```
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar
```

## अब आप उपयोग कर सकते हैं निष्पादित:
```
$ php drupal.phar
```

यदि आप चाहें कहीं भी इस फाइल को रख सकते हैं| अगर आप इसको अपने पथ में डालते हो तो, आप इसको सार्वभौमिक रूप से उपयोग कर सकते हैं. Unixy सिस्टम पर आप भी यह निष्पादन योग्य बना सकते हैं और बिना PHP आह्वान किये हुए|

### आपके सिस्टम पर कहीं से भी एक्सेस
```
$ mv drupal.phar /usr/local/bin/drupal
```

### डाउनलोड की गई फ़ाइल पर निष्पादन अनुमतियाँ लागू करें:
```
$ chmod +x /usr/local/bin/drupal
```

#### अब आप उपयोग कर सकते हैं निष्पादित:
```
$ drupal
```

**NOTE:** नाम `drupal` सिर्फ एक उपनाम आप यह आप की तरह कुछ भी नाम दे सकते हैं|