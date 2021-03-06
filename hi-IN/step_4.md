## टीम बनाएं

सिंक्रोनाइज्ड स्विमिंग को एक से अधिक बिल्ली की जरूरत है! हम `create clone of`{:class="block3control"} कोड का प्रयोग करेंगे जिस से ऐसी कॉपीज़ बनाएंगे ।

--- task ---

सबसे पहले यह सुनिश्चित (sure) करने के लिए कोड जोड़ें कि जब आप हरी झंडी पर क्लिक करते हैं तो बिल्ली हमेशा उसी स्थिति  (position) में शुरू हो

![तैराक स्प्राइट](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
```

--- /task ---

--- task ---

कोड का परिक्षण करने के लिए कुछ एरो बटन्स दबा कर और फिर फिर स्टार्ट पोजीशन पर वापिस जाने के लिए हरे झंडे पर क्लिक करें ।

--- /task ---

--- task ---

अब हम `repeat`{:class="block3control"} कोड का उपयोग कर के लूप करने के लिए बिल्ली की ६ कॉपीज़ बना लेंगे ।

![तैराक स्प्राइट](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
+repeat (6)
create clone of (myself v)
end
```

कई बार एक ही काम को बार बार करने के लिए लूप्स का उपयोग किया जाता है।

--- /task ---

--- task ---

आप सभी बिल्लियों को एक ही स्थिति में नहीं रखना चाहेंगे ।

प्रत्येक क्लोन बनाने से पहले 60 डिग्री को घुमाने के लिए कोड जोड़ें।

![तैराक स्प्राइट](images/swimmer-sprite.png)

```blocks3
when green flag clicked
go to x: (0) y: (0)
point in direction (90 v)
repeat (6)
+turn cw (60) degrees
create clone of (myself v)
end
```

--- /task ---

--- task ---

 एरो बटन का उपयोग करके अपने कोड का परीक्षण (test) करें। अब आप कुछ अद्भुत सिंक्रनाइज़ तैराकी पैटर्न बनाने में सक्षम होंगे ।

![6 बिल्ली सभी विभिन्न पदों और घुमावों में फैलाती हुई ।](images/swim-test-clones.png)

--- /task ---
