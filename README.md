## 🟡 Level 3 — Links & Images

HTML Links & Images are used to connect webpages, open websites, and display images on a webpage.

### 📚 Topics Covered

| #  | HTML Tag / Attribute | Description                            |
| -- | -------------------- | -------------------------------------- |
| 21 | `<a>`                | Creates a link                         |
| 22 | `href`               | Specifies the link destination         |
| 23 | `target`             | Specifies where to open the link       |
| 24 | `<img>`              | Displays an image                      |
| 25 | `src`                | Specifies the image source             |
| 26 | `alt`                | Provides alternative text for an image |
| 27 | `width` / `height`   | Controls image dimensions              |

---

### 🔹 21. `<a>` — Link

The `<a>` tag is used to create a **hyperlink**.

```html
<a href="https://www.google.com">Visit Google</a>
```

**বাংলা:** `<a>` tag ব্যবহার করে একটি webpage বা website-এর সাথে **link** তৈরি করা হয়।

---

### 🔹 22. `href` — Hyperlink Reference

The `href` attribute specifies the **destination URL** of a link.

```html
<a href="https://www.google.com">Google</a>
```

**বাংলা:** `href` বলে দেয় link-এ click করলে **কোন website বা webpage-এ যেতে হবে**।

---

### 🔹 23. `target` — Link Target

The `target` attribute specifies **where the linked page will open**.

```html
<a href="https://www.google.com" target="_blank">
    Open Google
</a>

```

**বাংলা:** `target` দিয়ে link-টি কোথায় open হবে তা নির্ধারণ করা যায়।

#### Common Target Values

| Target    | কাজ                                |
| --------- | ---------------------------------- |
| `_blank`  | নতুন tab-এ open করে                |
| `_self`   | একই tab-এ open করে                 |
| `_parent` | Parent browsing context-এ open করে |
| `_top`    | পুরো window-তে open করে            |

Example:

```html
<a href="https://www.google.com" target="_blank">
    Open Google in New Tab
</a>
```

---

### 🔹 24. `<img>` — Image

The `<img>` tag is used to **display an image** on a webpage.

```html
<img src="image.jpg" alt="A beautiful image">
```

**বাংলা:** `<img>` tag ব্যবহার করে webpage-এর মধ্যে **image দেখানো হয়**।

> 💡 `<img>` is a void element, so it does not need a closing tag like `</img>`.

---

### 🔹 25. `src` — Image Source

The `src` attribute specifies the **location or URL of the image**.

```html
<img src="photo.jpg" alt="My Photo">
```

**বাংলা:** `src` বলে দেয় **কোন image file বা image URL থেকে ছবি load করতে হবে**।

Example with a folder:

```html
<img src="images/photo.jpg" alt="My Photo">
```

---

### 🔹 26. `alt` — Alternative Text

The `alt` attribute provides **alternative text** for an image.

```html
<img src="cat.jpg" alt="A white cat">
```

**বাংলা:** `alt` image সম্পর্কে একটি **বর্ণনা** দেয়। কোনো কারণে image load না হলে এই text দেখা যেতে পারে।

It also helps with **accessibility**, especially for users who use screen readers.

---

### 🔹 27. `width` / `height` — Image Dimensions

The `width` and `height` attributes specify the **size of an image**.

```html
<img 
    src="photo.jpg" 
    alt="My Photo" 
    width="300" 
    hei
ght="200"
>
```

**বাংলা:** `width` দিয়ে image-এর **প্রস্থ (Width)** এবং `height` দিয়ে image-এর **উচ্চতা (Height)** নির্ধারণ করা হয়।

---

## 🔗 Complete Link Example

```html
<a 
    href="https://github.com/" 
    target="_blank"
>
    Visit GitHub
</a>
```

**বাংলা:** এখানে `href` GitHub-এর address দিয়েছে এবং `target="_blank"` ব্যবহার করার কারণে link-টি নতুন tab-এ open হবে।

---

## 🖼️ Complete Image Example

```html
<img 
    src="profile.jpg" 
    alt="My Profile Photo" 
    width="300" 
    height="300"
>
```

**বাংলা:**

* `src` → কোন ছবি দেখাবে
* `alt` → ছবির description
* `width` → ছবির প্রস্থ
* `height` → ছবির উচ্চতা

---

## 🔗🖼️ Link + Image Together

An image can also be used as a link.

```html
<a href="https://github.com/" target="_blank">
    <img 
        src="github-logo.png" 
        alt="GitHub Logo" 
        width="100"
        height="100"
    >
</a>
```

**বাংলা:** এখানে image-এর উপর click করলে GitHub website open হবে।

---

## 🧠 Quick Reference

```text
<a>             → Creates a link
href             → Link destination
target           → Where the link opens
<img>            → Displays an image
src              → Image source
alt              → Alternative text
width            → Image width
height           → Image height
```

---

## 🎯 Practice

Create a new HTML file and practice:

1. Create a link to Google.
2. Open a link in a new tab using `target="_blank"`.
3. Add an image using `<img>`.
4. Use `src` to load an image.
5. Add meaningful `alt` text.
6. Set image `width` and `height`.
7. Make an image clickable by placing `<img>` inside `<a>`.

**Next:** 🟡 Level 4 — Lists
