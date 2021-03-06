[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Ruby Class Methods

## Objectives

By the end of this, students should be able to:

-   Give an example of a class method you already use.
-   Diagram the invocation pattern between `#initialize` and `.new`.
-   Contrast defining class methods with defining instance methods.
-   Contrast invoking class methods with invoking instance methods.

## Class Methods

Sometimes a method is associated with a class, not an object.

Observe how a Method on a **Class** differs from a method on an **Instance**
that Class.

Let's discuss the code below:

```ruby
class FullCat
  def self.mouse
    puts "I'm in the cats stomach"
  end

  def escape_mouse
    puts 'I escaped the cat'
  end
end
```

## Demonstration

Let's take a look at the code in `lib/custom_attr.rb`

## Lab: Making a Class Method

-   Make a class method on Album to search the collection of albums by `title`.
-   Use this class method to set YOUR favorite Album by searching for the album
title.
-   Create a instance method on songs to add a `Rating` to Songs.

## [License](LICENSE)

1.  All content is licensed under a CC­BY­NC­SA 4.0 license.
1.  All software code is licensed under GNU GPLv3. For commercial use or
    alternative licensing, please contact legal@ga.co.
