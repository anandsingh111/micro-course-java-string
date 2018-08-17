>>Consider the following code:

```
String varOne = new String("Hi There");
String varTwo = new String("Hi There");
String varThree = varOne;
```

<p>After this code is executed, which of the following statements will evaluate to TRUE?</p>
<p>I. <code>varOne == varTwo</code><br/>
II. <code>varOne.equals(varTwo)</code><br/>
III. <code>varOne == varThree</code><br/>
IV. <code>varTwo.equals(varThree)</code></p><<

( ) II {{Incorrect because III and IV will also evaluate to true as all three strings hold the value "Hi There".}}
( ) IV {{Incorrect because II and III will also evaluate to true as all three strings hold the value "Hi There".}}
( ) II and IV {{Incorrect because III will also evaluate to true as the reference for <code>varOne</code> and <code>varThree</code> are the same.}}
(x) II, III and IV {{Correct because all three variables hold the same value, and the reference for <code>varOne</code> and <code>varThree</code> is the same.}}
( ) I, II and III {{Incorrect because I will evaluate to false due to the fact that <code>varOne</code> and <code>varTwo</code> don't share the same reference.}}

||"==" compares the reference while <code>.equals()</code> compares the values inside the <code>String</code>. ||
