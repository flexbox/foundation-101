# API Form endpoint for hamid

Setting it up is easy and free. Here's how:

### 1. Choose a service

We are going to take [formspree](https://formspree.io/). Setting it up is easy and free.

### 2. Setup the HTML form

Change your form's `action`attribute to this and replace **your@email.com** with your own.

```html
<form accept-charset="UTF-8" action="https://formspree.io/your@email.com" method="POST">
```

### 3. Add a name attribute to every field

Ensure all `<input>`, `<select>` and `<textarea>` elements inside your form have a name attribute, otherwise you will not receive the data filled in these fields.

### 4. Submit the form and confirm your email address

Go to your website and submit the form once. This will send you an email asking to confirm your email address.

### 5. All set, receive emails

From now on, when someone submits that form, we'll forward you the data as email.

