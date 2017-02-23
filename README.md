# sreenivasan-web
Website for Sreenivasan Lab

Preview link -> [click here](http://thecodeater.github.io/sreenivasan-web)

## Guide

### Text block with colored background

If you want to create a text block with background color, use following template:

```html
<div class="bg-default alert">
  <p>In the Sreenivasan lab, we are interested in how the brain <strong>forms and implements goals</strong>. Our primary focus is the neurobiological basis of <strong>working memory</strong>, which is the process that allows us to actively hold on to information over brief periods. Working memory is what underlies our ability to communicate, to problem solve, and to think abstractly. </p>
  <p class="mb-0">The Sreenivasan lab is a part of the Division of Science and Mathematics at New York University Abu Dhabi <a href="about.html">[more]</a></p>
</div>
```
> To change the default background color, change `bg-default` to `bg-blue`, `bg-red`, `bg-yellow`, `bg-green`, `bg-none`. Other custom background colors can be added upon request.

> `<p>` refers to the opening of the paragraph tag, and `</p>` refers to the corresponding closing tag.

###### Preview

**bg-default** <br/>
<img width="767" alt="screen shot 2017-02-23 at 11 35 58 am" src="https://github.abudhabi.nyu.edu/storage/user/63/files/5af86ecc-f9bc-11e6-9a31-93ff7e1b81a6">

**bg-red** </br>
<img width="765" alt="screen shot 2017-02-23 at 11 36 19 am" src="https://github.abudhabi.nyu.edu/storage/user/63/files/5ad5f928-f9bc-11e6-8b67-dacdeb95c365">

### List

To create a list, use the following template:

```html
<div class="list">
  <h3> List title </h3>
  
  <ul>
    <li> List item 1 </li>
    <li> List item 2 </li>
    <li> List item 3 </li>
  </ul>
</div>
```

> `<li>` refers to the beginning of the list item, and `</li>` refers to its corresponding end.

###### Example
```html
<div class="list">
	<h3>2014</h2>

	<ul>
		<li>
			<strong>Sreenivasan KK</strong>, Curtis CE, and D’Esposito M (2014). Revisiting the role of persistent neural activity during working memory. <span class="font-italic">Trends in Cognitive Sciences, 18(2)</span>, 82-89
		</li>
		<li>
			<strong>Sreenivasan KK</strong>, Gratton C, Vytlacil J, and D’Esposito M (2014). Evidence for working memory storage operations in perceptual cortex. <span class="font-italic">Cognitive, Affective &amp; Behavioral Neuroscience, 14(1)</span>, 117- 128.
		</li>
		<li>
			Cohen JR*, <strong>Sreenivasan KK</strong>, and D’Esposito M (2014). Correspondence between stimulus encoding- and maintenance-related neural processes underlies successful working memory. <span class="font-italic">Cerebral Cortex, 24(3)</span>, 593-599. *contributed equally; co-first authors
		</li>
		<li>
			<strong>Sreenivasan KK</strong>, Vytlacil J, and D’Esposito M. (2014). Distributed and dynamic coding of working memory stimulus representations in extrastriate cortex. <span class="font-italic">Journal of Cognitive Neuroscience, 26(5)</span>, 1141-1153.
		</li>
	</ul>
</div>
```

> `<strong></strong>` is used to make a text bold. <br/>
> `<span class="font-italic"></span>` is used to make the text italic. <br/>
> Only the text within the two opening and closing tags is affected.

###### Preview
The above code will look something as follows:

<img width="782" alt="screen shot 2017-02-23 at 11 31 16 am" src="https://github.abudhabi.nyu.edu/storage/user/63/files/f64f71aa-f9bb-11e6-9c16-9322b68bce92">
