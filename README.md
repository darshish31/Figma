# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
HOME PAGE

<div data-layer="Android Compact - 1" className="AndroidCompact1" style={{width: 360, height: 640, position: 'relative', background: '#B18093', border: '1px black solid'}}>
  <img data-layer="logo 1" className="Logo1" style={{width: 345, height: 52, left: 8, top: 36, position: 'absolute'}} src="https://via.placeholder.com/345x52" />
  <div data-layer="REGISTER!!!" className="Register" style={{width: 216, height: 45, left: 82, top: 384, position: 'absolute', textAlign: 'center', color: 'black', fontSize: 36, fontFamily: 'Italiana', fontWeight: '400', wordWrap: 'break-word'}}>REGISTER!!!</div>
  <div data-layer="Canvas & Creativity: Unleash Your Inner Self" className="CanvasCreativityUnleashYourInnerSelf" style={{width: 345, height: 86, left: 8, top: 183, position: 'absolute', textAlign: 'center', color: 'black', fontSize: 36, fontFamily: 'Jim Nightshade', fontWeight: '400', wordWrap: 'break-word'}}>Canvas & Creativity: Unleash Your Inner Self</div>
  <div data-layer="Rectangle 1" className="Rectangle1" style={{width: 258, height: 79, left: 56, top: 371, position: 'absolute', opacity: 0.23, background: '#7A4E82'}} />
</div>

/* Android Compact - 1 */

box-sizing: border-box;

position: relative;
width: 360px;
height: 640px;

background: #B18093;
border: 1px solid #000000;


/* logo 1 */

position: absolute;
width: 345px;
height: 52px;
left: 8px;
top: 36px;

background: url(logo.png);


/* REGISTER!!! */

position: absolute;
width: 216px;
height: 45px;
left: calc(50% - 216px/2 + 10px);
top: 384px;

font-family: 'Italiana';
font-style: normal;
font-weight: 400;
font-size: 36px;
line-height: 42px;
text-align: center;

color: #000000;



/* Canvas & Creativity: Unleash Your Inner Self */

position: absolute;
width: 345px;
height: 86px;
left: 8px;
top: 183px;

font-family: 'Jim Nightshade';
font-style: normal;
font-weight: 400;
font-size: 36px;
line-height: 51px;
text-align: center;

color: #000000;



/* Rectangle 1 */

position: absolute;
width: 258px;
height: 79px;
left: 56px;
top: 371px;

background: #7A4E82;
opacity: 0.23;


PAGE 2

<div data-layer="Android Compact - 2" className="AndroidCompact2" style={{width: 360, height: 640, position: 'relative', background: '#7A4E82'}}>
  <div data-layer="Ellipse 1" className="Ellipse1" style={{width: 300, height: 558, left: 35, top: 38, position: 'absolute', opacity: 0.34, background: '#D9D9D9', borderRadius: 9999}} />
  <div data-layer="EVENTS CONDUCTED" className="EventsConducted" style={{width: 520, left: -80, top: 38, position: 'absolute', textAlign: 'center', color: 'white', fontSize: 36, fontFamily: 'Italiana', fontWeight: '400', wordWrap: 'break-word'}}>EVENTS CONDUCTED</div>
  <div data-layer=">Crochet for beginners >Mini canvas painting >Clay Art >Pottery Making >Fun Art Experiments >Digital Art >Show and Tell >Artwork stalls" className="CrochetForBeginnersMiniCanvasPaintingClayArtPotteryMakingFunArtExperimentsDigitalArtShowAndTellArtworkStalls" style={{width: 281, height: 467, left: 41, top: 104, position: 'absolute', color: '#460249', fontSize: 20, fontFamily: 'Instrument Sans', fontWeight: '400', wordWrap: 'break-word'}}>>Crochet for beginners<br/><br/>>Mini canvas painting<br/><br/>>Clay Art<br/><br/>>Pottery Making<br/><br/>>Fun Art Experiments<br/><br/>>Digital Art<br/><br/>>Show and Tell<br/><br/>>Artwork stalls</div>
</div>

/* Android Compact - 2 */

position: relative;
width: 360px;
height: 640px;

background: #7A4E82;


/* Ellipse 1 */

position: absolute;
width: 300px;
height: 558px;
left: 35px;
top: 38px;

background: #D9D9D9;
opacity: 0.34;


/* EVENTS CONDUCTED */

position: absolute;
width: 520px;
height: 42px;
left: -80px;
top: 38px;

font-family: 'Italiana';
font-style: normal;
font-weight: 400;
font-size: 36px;
line-height: 42px;
text-align: center;

color: #FFFFFF;



/* >Crochet for beginners >Mini canvas painting >Clay Art >Pottery Making >Fun Art Experiments >Digital Art >Show and Tell >Artwork stalls */

position: absolute;
width: 281px;
height: 467px;
left: 41px;
top: 104px;

font-family: 'Instrument Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;

color: #460249;

PAGE 3:

<div data-layer="Android Compact - 3" className="AndroidCompact3" style={{width: 360, height: 640, position: 'relative', background: '#705598'}}>
  <div data-layer="DATA FORM" className="DataForm" style={{width: 302, height: 46, left: 27, top: 38, position: 'absolute', textAlign: 'center', color: 'white', fontSize: 36, fontFamily: 'Italiana', fontWeight: '400', wordWrap: 'break-word'}}>DATA FORM</div>
  <div data-layer="Name: DepartmentT: Event(1 per person): Mobile No.: Email:" className="NameDepartmenttEvent1PerPersonMobileNoEmail" style={{width: 316, height: 351, left: 22, top: 105, position: 'absolute', color: 'white', fontSize: 32, fontFamily: 'Jersey 15', fontWeight: '400', wordWrap: 'break-word'}}>Name:<br/><br/>DepartmentT:<br/><br/>Event(1 per person):<br/><br/>Mobile No.:<br/><br/>Email:</div>
  <div data-layer="Rectangle 2" className="Rectangle2" style={{width: 224, height: 45, left: 105, top: 117, position: 'absolute', background: '#D9D9D9'}} />
  <div data-layer="Rectangle 3" className="Rectangle3" style={{width: 217, height: 36, left: 112, top: 202, position: 'absolute', background: '#D9D9D9'}} />
  <div data-layer="Rectangle 4" className="Rectangle4" style={{width: 208, height: 31, left: 121, top: 268, position: 'absolute', background: '#D9D9D9'}} />
  <div data-layer="Rectangle 5" className="Rectangle5" style={{width: 184, height: 45, left: 154, top: 320, position: 'absolute', background: '#D9D9D9'}} />
  <div data-layer="Rectangle 6" className="Rectangle6" style={{width: 242, height: 46, left: 87, top: 398, position: 'absolute', background: '#D9D9D9'}} />
</div>

/* Android Compact - 3 */

position: relative;
width: 360px;
height: 640px;

background: #705598;


/* DATA FORM */

position: absolute;
width: 302px;
height: 46px;
left: 27px;
top: 38px;

font-family: 'Italiana';
font-style: normal;
font-weight: 400;
font-size: 36px;
line-height: 42px;
text-align: center;

color: #FFFFFF;



/* Name: DepartmentT: Event(1 per person): Mobile No.: Email: */

position: absolute;
width: 316px;
height: 351px;
left: 22px;
top: 105px;

font-family: 'Jersey 15';
font-style: normal;
font-weight: 400;
font-size: 32px;
line-height: 32px;

color: #FFFFFF;



/* Rectangle 2 */

position: absolute;
width: 224px;
height: 45px;
left: 105px;
top: 117px;

background: #D9D9D9;


/* Rectangle 3 */

position: absolute;
width: 217px;
height: 36px;
left: 112px;
top: 202px;

background: #D9D9D9;


/* Rectangle 4 */

position: absolute;
width: 208px;
height: 31px;
left: 121px;
top: 268px;

background: #D9D9D9;


/* Rectangle 5 */

position: absolute;
width: 184px;
height: 45px;
left: 154px;
top: 320px;

background: #D9D9D9;


/* Rectangle 6 */

position: absolute;
width: 242px;
height: 46px;
left: 87px;
top: 398px;

background: #D9D9D9;

PAGE 4:

<div data-layer="Android Compact - 4" className="AndroidCompact4" style={{width: 360, height: 640, position: 'relative', background: '#865383'}}>
  <div data-layer="THANK YOU" className="ThankYou" style={{width: 334, height: 166, left: 26, top: 211, position: 'absolute', color: 'white', fontSize: 40, fontFamily: 'Jomhuria', fontWeight: '400', wordWrap: 'break-word'}}><br/>                   THANK YOU</div>
</div>

/* Android Compact - 4 */

position: relative;
width: 360px;
height: 640px;

background: #865383;


/* Star 1 */

position: absolute;
width: 212px;
height: 225px;
left: 75px;
top: 164px;

background: #D9D9D9;
opacity: 0.34;


/* THANK YOU */

position: absolute;
width: 334px;
height: 166px;
left: 26px;
top: 211px;

font-family: 'Jomhuria';
font-style: normal;
font-weight: 400;
font-size: 40px;
line-height: 40px;

color: #FFFFFF;


```


## OUTPUT:
![alt text](<Screenshot 2024-12-22 130445.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
