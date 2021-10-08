<div align="center">
    <img src="https://cdn-icons-png.flaticon.com/512/1039/1039328.png" width="300px" height="280px"> <br> <br>
    <h1>
        EstJ
    </h1>
</div>

<br>
<br>

### 🍪 Description <br>

It's a simple javascript test framework, with purpose be able people execute tests simply and fast!

<br>

### 🌉 Usage <br>

It will find all files like it: \*.test.js, just run:

```
estj
```

<br>

-   To validate the tests it uses the nodejs assert, but its globally, you do not need to require it;
-   To create a test use the function it();
-   You can use beforeEach, it will execute before all tests;

<br>
Example:
<br>

```
beforeEach(() => {
    console.log('I am executing before a test')
})

it('should assert if 1 === 1', () => {
    assert.equal(1, 1)
})
```

<br>

### 🎗️ See It <br>


https://user-images.githubusercontent.com/82950902/136037222-80a7e85f-4bd7-4721-abe7-4d04f062627c.mp4


<br>

### 🎠 Author

Nathan Cotrim - MIT
