## चुनौती: अपना रूटीन कोड करें

जब आप स्पेस की या किसी अन्य बटन को दबाते हैं तो क्या आप अपनी खुद की सिंक्रोनाइज्ड स्विमिंग रुटीन लिख सकते हैं?

पहले तीर बटनो का उपयोग करके एक रूटीन बनाने की कोशिश करें।

`repeat`{:class="block3control"} कोड एक ही एक्शन को बार बार रिपीट करने में मदद करता है I

यहाँ एक उदाहरण है:

![तैराक स्प्राइट](images/swimmer-sprite.png)

```blocks3
when [m v] key pressed
repeat (8)
    turn cw (45) degrees
    repeat (20)
        move (5) steps
    end
    repeat (20)
        move (-5) steps
    end
end
```

