## Nano costumes ని మార్చుకుంటుంది

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

**costumes** ని మార్చడం ద్వారా మీరు Nanoని emote గా పొందుతారు.

Sprite లు కనిపించే విధానాన్ని మార్చడానికి **costumes**ని కలిగి ఉంటాయి. sprite ను యానిమేట్ చేయడానికి, మీరు దాని costume లను మార్చవచ్చు.

</div>
<div>

![Nano sprite చెప్తోంది, "Thanks!"](images/nano-step-2.png){:width="300px"}

</div>
</div>

### Nano చెప్తోంది "Thanks!"

--- task ---

**Fantasy** వర్గం నుండి మీ ప్రాజెక్ట్‌కి **Nano** sprite ని జోడించండి.

!['Choose a Sprite' చిహ్నం.](images/choose-sprite-menu.png)

--- /task ---

--- task ---

Stage దిగువన ఉన్న Sprite జాబితాలో **Nano** sprite ఎంచుకోబడిందని నిర్ధారించుకోండి.

![Sprite జాబితాలో, Nano ఎంపిక చేయబడిందని చూపించడానికి Nano sprite చుట్టూ నీలిరంగు అంచుతో ఉంటుంది.](images/nano-selected.png)


**Code** ట్యాబ్‌పై క్లిక్ చేసి, **Nano** sprite నుండి `say`{:class="block3looks"} `Thanks!`ని పొందడానికి స్క్రిప్ట్‌ను జోడించండి:

![Nano sprite.](images/nano-sprite.png)

```blocks3
when this sprite clicked // when Nano is clicked
switch costume to [nano-b v] // Nano talking
say [Thanks!] for [2] seconds // try 1 instead of 2
switch costume to [nano-a v] // Nano smiling
```
--- /task ---

**చిట్కా:** అన్ని బ్లాక్స్, విభిన్న రంగులను కలిగి ఉంటాయి కాబట్టి మీరు, `switch costume to`{: class = "block3looks"} బ్లాక్ ను `Looks`{: clas = "block3looks"} బ్లాక్స్ మెనులో కనుగొంటారు.

--- task ---

**పరీక్ష:** **Nano** sprite పై క్లిక్ చేసి, స్పీచ్ బబుల్ రెండు సెకన్ల పాటు కనిపిస్తుందో లేదో తనిఖీ చేయండి.

--- /task ---

### Nano సంకేత భాషను ఉపయోగిస్తుంది

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">కమ్యూనికేట్ చేయడానికి మిలియన్ల మంది ప్రజలు సంకేత భాషను ఉపయోగిస్తున్నారు. 'ధన్యవాదాలు' కోసం ఒక సాధారణ సంకేతం **మీ కుడి చేతిని మీ నోటిపైకి తీసుకురావడం**. 
</p>

Nano costumes మార్చడం ద్వారా సంకేత భాషను ఉపయోగిస్తుంది.

మీరు పెయింట్ ఎడిటర్‌తో మీ sprite ల కోసం costume లను సవరించవచ్చు. "ధన్యవాదాలు" అని సంకేతం చేయడానికి మీరు Nano costume లను ఎడిట్ చేస్తారు.

--- task ---

**Nano** sprite కోసం costume లను చూడటానికి **Costumes** ట్యాబ్‌పై క్లిక్ చేయండి:

![Nano sprite కోసం అందుబాటులో ఉన్న costumes.](images/nano-costumes.png)

--- /task ---

--- task ---

**nano-b** costume పై క్లిక్ చేయండి. ఎడమ వైపున ఉన్న చేతిపై క్లిక్ చేసి, ఆపై **Delete**పై క్లిక్ చేయండి.

![చేతిని కలిగిన nano-b costume ఎంపిక చేయబడింది.](images/nano-arm-selected.png)

costume ఇలా కనిపించాలి:

![చేతితో ఉన్న nano-b costume తొలగించబడింది.](images/nano-arm-deleted.png)

--- /task ---

**చిట్కా:** మీరు పెయింట్ ఎడిటర్‌లో పొరపాటు చేస్తే, మీరు **Undo**పై క్లిక్ చేయవచ్చు.

!['Undo' చిహ్నం.](images/nano-undo.png)

--- task ---

**nano-c** costume కి వెళ్లి, ఎడమ వైపున ఉన్న చేతిపై క్లిక్ చేసి, ఆపై **Copy**పై క్లిక్ చేయండి.

![చేతిని కలిగిన nano-c costume ఎంపిక చేయబడింది.](images/nano-c-arm-selected.png)

--- /task ---

--- task ---

**nano-b** costume కి తిరిగి వెళ్లి, **Paste**పై క్లిక్ చేయండి. costume ఇలా కనిపించాలి:

![nano-c costume నుండి తీసుకొన్న చేతితో nano-b costume.](images/nano-b-new-arm.png)

--- /task ---

--- task ---

**పరీక్ష:** Stage పై గల **Nano** sprite పై క్లిక్ చేసి, స్పీచ్ బబుల్ కనిపిస్తుందో లేదో తనిఖీ చేయండి మరియు మీరు ఎడిట్ చేసిన costume కి Nano costume మారుతుందో లేదో తనిఖీ చేయండి.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">"ధన్యవాదాలు" అని ఎలా సంకేతం చేయాలో మీరు నేర్చుకున్నారు. తదుపరిసారి మీరు ఎవరికైనా ధన్యవాదాలు చెప్పడానికి, మీ కొత్త నైపుణ్యాన్ని ఎందుకు ఉపయోగించకూడదు?
</p>

--- save ---
