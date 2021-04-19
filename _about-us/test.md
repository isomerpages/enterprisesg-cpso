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
    margin: 0 0 1px 0;
    cursor: pointer;
    background: #6AAB95;
    border-radius: 3px;
    color: #FFF;
    transition: ease .5s;
    font-size: 1.5em;
    position: relative;
}

label:hover {
    background: #4E8774;
}

label::after {
    content: '+';
    font-size: 22px;
    font-weight: bold;
    position: absolute;
    right: 10px;
    top: 7px;
}

input:checked + label::after {
    content: '-';
    right: 14px;
    top: 7px;
}

.content {
    background: #E2E5F6;
    padding: 10px 25px;
    border: 1px solid #A7A7A7;
    margin: 0 0 1px 0;
    border-radius: 3px;
}

input + label + .content {
    display: none;
}

input:checked + label + .content {
    display: block;
}

</style>

        <input type="checkbox" id="title1" /><label for="title1">Accordion One</label>
        <div class="content">
            <p>Your content goes here inside this division with the class "content".</p>
        </div>

        <input type="checkbox" id="title2" /><label for="title2">Accordion Two</label>
        <div class="content">
            <p>Your content goes here inside this division with the class "content".</p>
        </div>
