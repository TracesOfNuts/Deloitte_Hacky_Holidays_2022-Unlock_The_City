![challenge](./img/Capture.PNG)

\#web

#### CHALLENGE INFORMATION

You ended up at the port of the hyperintelligent smart city and are trying to pass the customs check point.

The smart city is on a tight leash and strangers are no longer allowed to enter until the city is under control. You notice that people must show their shield with a strange emblem before they are allowed to enter the city. Drastic times call for drastic measures, can you hack your way into the city in an attempt to bring the city back under control?

---

#### ENTER FLAGS

###### [50 POINTS] IDENTIFY  YOURSELF

Open the [shield designer](https://portal.hackazon.org/?login#!/shielddesigner) and see if you can hack your way into the city.

Note: Only the URL https://portal.hackazon.org/shielddesigner and its sub-URLs are part of the teaser challenge.

---

#### FILES

[admin_shield.png](./src/admin_shield.png)

---

#### SOLUTION

Opening the [shield designer](./src/Shield Designer.html) page, shows us a UI to create a shield. The objective is to create the shield as shown in [admin_shield.png](./src/admin_shield.png). However, we notice that there are no available options to create - there are no options to create the icon in the middle nor is there an option to choose orange as a color.

First instinct is to inspect the HTML and CSS code using the 'inspect' feature on Google Chrome because there maybe obfuscated/hidden options.

We then can use the find to search for keywords such as "flag" or "hidden".

![before](./img/before.PNG)

Indeed, there is a class, 'ComponentPicker_hiddenShapeControl__NUlGd' and 'that has display set as 'none'. We can change it to 'block'. This will reveal the hidden options.

![before](./img/after.PNG)

We then can create the flag as shown in [admin_shield.png](./src/admin_shield.png).

This will reveal the flag.

![flag](./img/flag.PNG)

Flag:

```
CTF{4DM1N_4PPR0V3D}
```

---

#### References

