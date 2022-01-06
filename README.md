## 1.Heading
You can use one to six `#` sign for headings. So below codes

```
#heading 1

##heading 2

###heading 3

####heading 4

#####heading 5

######heading 6
```

will ends to 

# heading 1
## heading 2
### heading 3
#### heading 4
##### heading 5
###### heading 6

## 2. Quote
We have to type of quoting. 

#### 2.1 Quoting Text
You can quote with `>` sign

`> This is my Quote`

> This is my Quote

#### 2.2 Quoting Code
Fo r quoting code you should just put the code between two backticks.

```
git status
git add
git commit
```

## 3. Link
You can create inline link using parentheses `()`  and shoing its text with `[]`.

`This is a link for [GitHub Pages](https://pages.github.com/).`

This is a link for [GitHub Pages](https://pages.github.com/).

## 4. Image

You can display an image by adding ! and wrapping the alt text in[ ]. Then wrap the link for the image in parentheses ().

`![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)`

![This is an image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ0BpUNOx1vq9D1SJ0c_ZftUovc7BGO0k6Ucg&usqp=CAU)

## 5. Short Keys

## 6. List
There is two kind of Lists. `Unordered Lists` & `Ordered Lists`.

#### 6.1 Unordered List
You can make unordered lists with `-` or `*`

```
- George Washington
- John Adams
- Thomas Jefferson
```

- George Washington
- John Adams
- Thomas Jefferson

#### 6.2 Ordered List
To making ordered list you can use numbers


```
1. George Washington
2. John Adams
2. Thomas Jefferson
```

1. George Washington
2. John Adams
2. Thomas Jefferson

## 7. Emoji
You can add emoji to your writing by typing :EMOJICODE:

Full list of available emoji and codes --> [Emoji-Cheat-Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md).

## 8. Ignore Formatting
You can ignore formatting by using `\` before signs.

> `We can use \*Toturials\* for this part`

We can use \*Toturials for this part

## 9. Code Blocks

for defining code blocks, you can use name of your language like this:

```javascript

require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html

```


```javascript
function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}
```

