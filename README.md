Question:1 List out the feature of HTML5.
Answer:- main feature of the html 5 are ges without the nedd for plugins like flash
Canvas Element :- HTML5 introduce the <canvas> element, which allows for dynamic, interactive graphics to be created and manipulated within a web page
Geolocation API:- HTMl5 provide an API for obtaining the user's location, enabling a web application to offer location based serivces.
Locan Storage :- HTMl5 provide an local storage API, which allows the storage of data on user's device imporving performance and reducing the need of round-trips to the server.
New structural element :- HTML5 intoduce the nes semantic element such as <header> <footer>, <nav>, and <articel> that makes easier to structre and organise ccontent to web page.
Form improvement :- HTML5 introduce severla improvement form, including new input type like date time and color as well as new attributes such as rewuired and autofocus.
Accessibility improvement :- HTML5 provides better support for accessibility, including the ability to provide alternative text for image and improved support for screen readers.

 QUESTION:2 WHAT ARE HTML ENTITES? LIST OUT 5 COMMONLY USED HTML ENTITIES.
 HTML Entites: HTML entites are special codes which represent that special charaters, symbol with spdecific meaning in HTML. They are used display character that might otherwise be iterpreted as HTML code or cause rendering issues in web browsers. HTML entites are written using an ampersand (&) followed by asoecific code  or name and ending with semicolon ().
 5 COMMONLY USED HTML ENTITES :- 
 &lt;- Repersents the less-than symnol>.
 Example <p> this is an example &lt;em&gt;text&lt;/em&gt;</p>
 &gt;- represent the greater than symbol >
 example:- <p> for more inforation, visit our website &gt;<a href="#"> here </a> </p>

 &amp;- represent the ampersand symbol &.
 example: <p> for the furter details, contact us &amp; we'll assist you.</p>

 &quot;-represent the double quotation mark"
 example: <p> title of the book is "John Wick". </p>              

 &copy;- represent the copyright symbol ©
 example: <p>&copy;2023 ACME Corporation. all right reserved.</p>


QUESTION:3  DEFINE ACCESIBILITY IN THE CONTEXT OF WEB DEVELOPMENT. WHY IT'S ESSENTIAL TO CREATE ACCESBILITY WESITES AND HOW IT BENIFIT DIFFERENT USER GROUP.
ANSWER:-   Assebility in web development is refers to designing and coding websites in a way that assures people with disbility can perceive, understandd and nevigate and  interact with digital content efficitively. It involves making web content inclsive and usable for everyone, regardless of their ability.

Importnace of Accesbile websites:
Inclusivity: Accessbility websites ensure that everyone, including people with disabilities, can access and use online information and services.
Legal Compliance: may counrties havae law requiring website to be accessible, avoiding leagal issue and promoting equal access.
User Experince: Accessible design often lead to improved user experince to everyone, including clear navigation and content structure.
Buisness Growth: Accessible website reach to wider audience, increasinf engagment, loyaltiy and potential customer base.

BENIFIT FOR USER GROUP:
Visual impairments: Accessbility provide screen reader support and text alternatives, aiding bling and visually impaired users.
Hearing Impairmnets: Captions and transcript benefit those with hearing impairments by maing audio content understandable.
Motor Disablity : Keyboard navigation and easy to click elements assist users with motor limitation.
Cognitive disability: Accessible design accommodate age-related limitations, ensuring usability for elderly users.
Mobile Users: Accessibile design improve mobile experincce through simplifed and responsive layouts.


QUESTION 4: lIST ANY 3 WAY WHICH HELP US IN IMPROVING THE ACCESSIBILTY OF HTML
ANSWER: Use Semantic HTML Element: Using HTMl elements help improves accessibilty by providing meaningful structure to your content. Semantic Element like <header> <nav>, <main>,<article> and <footer> convey the purpose of differnt section to assistive technlogies,maing to easier to navigate to users with disablities to navigate and understand the content.

Provide alt text for image : Adding descriptive alt text to image using the alt attribute ensure that users who cannot see the images can understand their content and purpose. screen reader read aloud to the alt text, making visual content accessible to people with visual impairments. Aim to make alt text concise, informative, and relevant to the image.

Use color with care: Colors play and important role in web design, but it should not be the only mean convey information. Ensure that color is not only the sole indicator of meaning. For example, When using error messages, pair color with text that explains the error. Additionaly, maintain sufficient color contrast between text and backgroud to  inhance readibility for users with low vision.

QUESTION 5: CREATE A WEB PAGE THAT HIGHLIGHTS THE FEATURE OF HTML5. USE APPROPRIATE SEMANTIC TAGS TO STRUCTURE THE CCONTENT AND SHOWCASE AT LEAST THREE KEY FEATUREA OF HTML5 WITH EXPLANATIONS. 
ANSWER
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Feature of HTMl5 </title>
</head>
<body>
<header>
<h1>Feature of HTMl5</h1>
<p>our web page feature with the help of HTMl5</p>
</header>
<section>
<h2>Feature 1: Video Playback</h2>
<p>
HTML5 introduced the <code>&lt;video&gt;</code> element for embedding
videos directly in web pages.
</p>
<video width="400" controls>
<source src="sample-video.mp4" type="video/mp4" />
Your browser does not support the video tag.
</video>
</section>
<section>
<h2>Feature 2: Form Validation</h2>
<p>
HTML5 offers built-in form validation, reducing the need for custom
JavaScript code.
</p>
<form>
<label for="email">Email:</label> 
<input type="email" id="email" required  placeholder="Email"/>
<br />
Assignment Solution

Full Stack Web Development

Output:
<input type="submit" value="Submit" />
</form>
</section>
<section>
<h2>Feature 3: Semantic Tags</h2>
<p>
HTML5 introduced semantic tags like <code>&lt;header&gt;</code>,
<code>&lt;nav&gt;</code>, <code>&lt;main&gt;</code>, and more, which
improve page structure and accessibility.
</p>
<article>
<h3>Article Title</h3>
<p>
This is a sample article content. Semantic tags make it easier to
structure your content and improve search engine optimization.
</p>
</article>
</section>
<footer>
<p>Created by VIKAS KUMAR &copy; 2023</p>
</footer>
</body>
</html>


QUESTION 6: CREATE A SIMPLE WEB PAGE WHICH HAS A TABLE. THE TABLE MUST HAVE 2 COLUMNS WHICH HAS HTML AND HTML5 THE TABLE SHOULD INCLUDE A MINIMUM OF THREE ROWS DESCRIBING THE DIFFERENCE BETWEEN HTML AND HTML5.
ANSWER: <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta http-equiv="X-UA-Compatible" content="IE=edge" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>HTML v/s HTML5</title>
</head>
<body>
<h1>HTML v/s HTML5</h1>
<table border="1">
<thead>
<tr>
<th>HTML</th>
<th>HTML5</th>
</tr>
</thead>
<tbody>
<tr>
<td>
It required plugins like Adobe Flash to support audio and video
content.
</td>
<td>
Provides built-in support for multimedia elements such as video and
audio without the need for a plugin.
</td>
</tr>
<tr>
<td>It has fewer elements as compared to HTML5.</td>
<td>
It includes new elements and form attributes such as time, date, and
colour. Required and autofocus in input types of the tag element as
well.
</td>
</tr>
<tr>
<td>It does not have support for local storage.</td>
<td>It has support for local storage i.e. localStorage.</td>
</tr>
Assignment Solution


Full Stack Web Development

<tr>
<td>
Less semantic elements, thereby providing less web accessibility
features.
</td>
<td>
<p>
It supports more semantic elements, such as &lt;header&gt;,
&lt;footer&gt;, &lt;nav&gt;, and &lt;article&gt;, thereby
improving accessibility.
</p>
</td>
</tr>
</tbody>
</table>
</body>
</html>
