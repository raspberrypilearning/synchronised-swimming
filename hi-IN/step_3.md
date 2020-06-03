## वेशभूषा बदलना

हम्म, यह बेहतर होगा अगर बिल्ली बाईं ओर मुड़ने पर दिशा बदल दे।

--- task ---

'कॉस्ट्यूम' पर क्लिक करें और 'कैट फ़्लाइंग-ए' कॉस्ट्यूम को हटा दें।

![पोशाक टैब और डिलीट (delete) आइकन पोशाक को हाईलाइट करें ।](images/swim-delete-a.png)

--- /task ---

--- task ---

बचे हुए पोशाक का बदल कर  नाम 'cat flying-a' से 'right' बदल कर रखदें ।

![पोशाक (costumes) टैब में सही नाम हाइलाइटेड ](images/swim-costume-right.png)

--- /task ---

--- task ---

पोशाक पर राइट-क्लिक करें और कॉपी बनाने के लिए डुप्लिकेट चुनें।

![कॉस्टयूम मेनू डुप्लिकेट के साथ हाइलाइट किया गया](images/swim-costume-duplicate.png)

--- /task ---

--- task ---

कॉपी को उलटने के लिए 'Flip Horizontal' पर क्लिक करें और फिर इसे 'left' नाम दें।

आपकी पोशाक इस तरह दिखनी चाहिए:

![नई पोशाक फ्लिप कर के बाएं तरफ मुड़ा हुआ और नाम हाइलाइटेड 
](images/swim-costume-left.png)

--- /task ---

--- task ---

अपने कोड पर लौटने के लिए 'Code' पर क्लिक करें और दिशा बदलने पर पोशाक को बदलने के लिए ब्लॉक जोड़ें।

![तैराक स्प्राइट](images/swimmer-sprite.png)

```blocks3
when [left arrow v] key pressed
+switch costume to (left v)
turn ccw (15) degrees

when [right arrow v] key pressed
+switch costume to (right v)
turn cw (15) degrees
```

--- /task ---

--- task ---

तीर बटन का उपयोग करके मंच के चारों ओर तैरकर अपने कोड का परीक्षण (test) करें।

![स्प्राइट बाईं ओर](images/swim-test-left.png)

--- /task ---
