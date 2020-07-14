# Markdown Wireframes


```diff
* Go to Login Page
* + Email should be focused
* - Parse number 0

```

The idea was how easy it would be, if there was a way to design rough wireframes while putting together thoughts. We usually use markdown to put together architecture ideas, and commit to github.

We have explored tools like mermaidjs etc., which can help drawing flowcharts, but they won't be rendered in github after pushing. It kinda becomes inflexible and also all the developers, architects who are involved should also install those tools to see what it means. 

```diff
+ That's when we felt, may be there should be a simple way where context itself should be sufficient to convey meaning, assuming that the readers are smart enough to put together and get used to it very quickly.
```

And we stumbled upon [https://github.com/brikis98/wmd](https://github.com/brikis98/wmd), though this tool generates html, this representation felt that it can be extended further.

### Examples

* [Authentication Wireframes](https://github.com/rjvim/markdown-wireframes/wiki/Authentication-Wireframes)

### References

##### Titles

- `*Welcome User*`

##### Input

- `Name: ______`

##### List

Can be used for dropdown, navigation menu etc.,

- `{ Male, Female, Others }`
- `{ Profile, Settings, Logout }`

##### Table

- = Name = Email = Status

If you have actions in any columns

- = Name = Email = Status = Actions [Edit] [Delete]

##### Button/Link/Action

- `[Submit]`
- `[Pay]`

#### Layouts

##### Header, Left Right Sidebars

```
*Page Title*

Top
--
Menu | Content | Sidebar
--
Footer
```

##### Only Top Navigation

```
*Page Title*

Top {Home, Logout}
--
Content
--
Footer
```

##### Only Left Navigation

```
*Page Title*

Sidebar {Logo, Menu, Logout} | Content
--
Footer
```


##### A page with table

```
*Page Title*

Top
--
*List of Users*

= Name = Email = Status = Actions [Edit] [Delete]
--
Footer
```
