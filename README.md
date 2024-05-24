# Bento Self
A Link in Bio. But Rich and Beautiful. Inspired from [bento.me](https://bento.me/en/home)

## Configuration

### 1. Header

```html
<!-- [1] Header -->

<header>

    <!-- [1.1] Image profile -->
    <img class="profile" src=" <!-- Link to image --> ">

    <!-- [1.2] Your name -->
    <h1>Lorem ipsum</h1>

    <!-- [1.3] A bit description -->
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>

</header>
```
![Screenshot Capture - 2024-05-24 - 15-28-14](https://github.com/LIGMATV/bento-self/assets/143163098/897d0fe9-81db-4185-8bf0-f97d1c4890fc)


### 2. Menu and Sections

```html
<!-- [2] Menu buttons -->

<div class="menu">

    <a href="#menu-1">Menu 1</a>
    <a href="#menu-2">Menu 2</a>
    <a href="#menu-3">Menu 3</a>

</div>


<!-- [0] First section -->

<section id="menu-1">
    <!-- Your widgets here... -->
</section>

<section id="menu-2">
    <!-- Your widgets here... -->
</section>

<section id="menu-3">
    <!-- Your widgets here... -->
</section>
```

### 3. Big widget

```html
<!-- [3] Big widget -->

<a href="https://example.com" widget="big">

    <!-- [3.1] Favicon -->
    <div class="favicon">
        <img src=" <!-- Link to image --> ">
    </div>

    <!-- [3.2] Name of site -->
    <p class="name">Example</p>

    <!-- [3.3] A bit url of site -->
    <p class="url">example.com</p>

    <!-- [3.4] Preview or some image from site -->
    <div class="preview">
        <img src=" <!-- Link to image --> ">
    </div>

</a>
```
![Screenshot Capture - 2024-05-24 - 15-24-45](https://github.com/LIGMATV/bento-self/assets/143163098/8a3533a7-e168-438f-8f61-93b02bf69b4b)

### 4. Bigger widget

```html
<!-- [4] Bigger widget -->

<a href="https://example.com" widget="bigger">

    <!-- [3.1] -->
    <div class="favicon">
        <img src=" <!-- Link to image --> ">
    </div>

    <!-- [3.2] -->
    <p class="name">Example</p>

    <!-- [3.3] -->
    <p class="url">example.com</p>

    <!-- [3.4] -->
    <div class="preview">
        <img src=" <!-- Link to image --> ">
    </div>

</a>
```
![Screenshot Capture - 2024-05-24 - 15-27-30](https://github.com/LIGMATV/bento-self/assets/143163098/9b235660-0a00-4acd-a18b-86278ef7b2b7)

### 5. Wide widget

```html
<!-- [5] Wide widget -->

<a href="https://example.com" widget="wide">

    <!-- [3.1] -->
    <div class="favicon">
        <img src=" <!-- Link to image --> ">
    </div>

    <!-- [3.2] -->
    <span class="name">Example</span>

</a>
```
![Screenshot Capture - 2024-05-24 - 15-30-40](https://github.com/LIGMATV/bento-self/assets/143163098/0d801533-c39a-4288-b32b-8800d22f5219)

#### 5.1 Wide note

```html
<!-- [5.1] [5]Wide widget contain notes -->
<a widget="wide">
    <h2>Hmmm... we need more <b>wider space!</b></h2>
    <code>print('Hello, world!')</code>
</a>
```

#### 5.2 Wide picture

```html
<!-- [5.2] [5]Wide widget contain picture -->
<a widget="wide">
    <img class="picture" src=" <!-- Link to image --> ">
</a>
```

![Screenshot Capture - 2024-05-24 - 15-32-35](https://github.com/LIGMATV/bento-self/assets/143163098/afe6fd81-4341-44b5-8ec5-e95c5ab9cfbc)

### 6. Medium widget and group

```html
<!-- [6] Group of medium widgets -->

<group>

<a href="https://example.com" widget="medium">

    <!-- [3.1] -->
    <div class="favicon">
        <img src=" <!-- Link to image --> ">
    </div>

    <!-- [3.2] -->
    <p class="name">Example</p>

    <!-- [3.3] -->
    <p class="url">example.com</p>

</a>

<a href="https://example.com" widget="medium">
     <!-- Your elements here -->
</a>

</group>
```
![Screenshot Capture - 2024-05-24 - 15-38-58](https://github.com/LIGMATV/bento-self/assets/143163098/2f5d3ea3-be10-4b67-b848-cb0418f30c0e)

#### 6.1 Medium note

```html
<group>

    <a widget="medium" 
        style="background-color: #5b5b5b; color: #fff;">
            <h2>Customize the note<em>!</em></h2>
    </a>

    <a widget="medium">
        <em>Another cool text that just work</em>
    </a>

</group>
```
Add ``<group>`` for every 2 medium widget.
```html
<group>

    <!-- [6.3] Centered text -->
    <a widget="medium" 
        style="text-align: center; display: flex; justify-content: center; align-items: center;">
            <h2>Anything centered</h2>
    </a>

   <a widget="medium">
       <!-- Your elements here -->
   </a>

</group>
```

### 6.2 Medium picture

```html
<group>
    <!-- [6.4] Medium widget contain picture -->
    <a widget="medium">
        <img class="picture" src=" <!-- Link to image --> ">
    </a>

   <a widget="medium">
       <!-- Your elements here -->
   </a>

</group>
```

![Screenshot Capture - 2024-05-24 - 15-49-06](https://github.com/LIGMATV/bento-self/assets/143163098/68f0bf69-55e0-4ca0-992b-7eaf931b9454)
![Screenshot Capture - 2024-05-24 - 15-40-04](https://github.com/LIGMATV/bento-self/assets/143163098/00ab52b4-f447-4961-8ff5-9e617584d83c)


### 7. Section title

```html
<!-- [7] Section title -->
<section-title>Section title</section-title>
```
![Screenshot Capture - 2024-05-24 - 15-48-02](https://github.com/LIGMATV/bento-self/assets/143163098/808cae31-32e2-47d1-838e-3c24003d0c6a)

### 8. Blockquote

```html
<!-- [8] Quote -->

<a widget="medium"
      style="background-color:#fff6e7;">

      <!-- [8.1] The quote
      <blockquote>So I'll go, I'll go, I will go, go, go <br>

      <!-- [8.2] Who quoting
      <sub>- Bastille</sub>

      </blockquote>

</a>
```

![Screenshot Capture - 2024-05-24 - 15-54-26](https://github.com/LIGMATV/bento-self/assets/143163098/49325244-4734-43c6-b6f7-2c689975b1f9)
