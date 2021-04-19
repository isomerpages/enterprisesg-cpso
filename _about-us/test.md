---
title: FAQ
permalink: /about/faq
---
<style>

input {
	display: none;
}
label {
	display: block;
	padding: 8px 22px;
	margin: 0 0 5px 0;
	cursor: pointor;
	background: #F0F4F6;
	border-radius: 3px;
	color: #484848;
	transition: ease .5s;
	font-size: 1.5em;
}

label:hover {
	background: #4a96b0;
	color: #FFF;
}

.accordion-content {
	/* background: #E2E5F6; */
	padding: 10px 0px 30px 30px;
	/* border: 1px solid #484848; */
	margin: 0 0 1px 0;
	border-radius: 3px;
}

input + label + .accordion-content {
	display: none;
}

input:checked + label + .accordion-content {
	display: none;
}

input:checked + label + .accordion-content {
	display: block;
}

</style>
<!-- End of accordion -->


<body>

<input type="checkbox" id="title1"  /><label for="title1">Title 1</label>
<div class="accordion-content">
	<p>Singapore will deepen research capabilities in climate science and study the impacts of climate change, particularly on South East Asia.</p>
</div>

<input type="checkbox" id="title2"  /><label for="title2">Title 2</label>
<div class="accordion-content"><i class="sgds-icon sgds-icon-chevron-down"></i>
	<p>my content 2 my content 2 my content 2 my content 2</p>
</div>

</body>
