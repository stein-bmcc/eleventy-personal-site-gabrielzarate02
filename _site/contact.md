---
title: Contact
date: Created
layout: base
tags:
  - contact
---
<style>
    body{
        text-align: center;
    }
</style>

<h1>Contact Me!</h1>
        <!-- contact form--> 
    <form netlify data-netlify-recaptcha="true" id="contact">
        <section>
            <div class="contactform">
                <div class="row">
                    <div>
                         <label for="name">Name</label>
                        <input class="row1" type="text" class="info">
                 </div>  
                 <div>
                    <label for="org">Organization</label>
                    <input class="row1" type="text" class="info">
                    </div>
                </div>  
            
                    <div class="email">
                        <label for="email">Email</label>
                        <input type="text" class="email">
                    </div>
                    <div class="msg">
                        <label for="msg">Leave me a message!</label>
                        <input class="message" type="text">
                    </div>
                <div>
                    <input id="btn" type="submit" text="Submit">
                </div>
                 
            </div>
        </section>
        </form>                                 