---
layout: default
title: Home
sort_order: 0
show-nav: true
---
Lorem Ipsum Generator on www.lorem-ipsum.ch Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Donec hendrerit tempor tellus. Donec pretium posuere tellus. Proin quam nisl, tincidunt et, mattis eget, convallis nec, purus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nulla posuere. Donec vitae dolor. Nullam tristique diam non turpis. Cras placerat accumsan nulla. Nullam rutrum. Nam vestibulum accumsan nisl.

This text has been used since the 16th Century as a dummy text when you are preparing the layout of some presentation but don’t have the final text yet, or want to demonstrate the layout without distracting the reader with actual content.

The lorem ipsum text originated from “de Finibus Bonorum et Malorum” (The Extremes of Good and Evil) by Marcus Tullius Cicero, written in 45 BC but it has been so transformed along the years that now, it is relatively meaningless.

To insert lorem ipsum text in your emacs buffer, use Lisp:lorem-ipsum.el

Three functions are available:

Lorem-ipsum-insert-paragraphs
Lorem-ipsum-insert-sentences
Lorem-ipsum-insert-list
All can take a prefix argument to specify the number of paragraphs/sentences/items to insert.

The following (buffer-local) variables are available to customize the output to your need:

Lorem-ipsum-paragraph-separator (default value: “\n\n”)
Lorem-ipsum-sentence-separator (default value: “ “)
Lorem-ipsum-list-beginning (default value: “”)
Lorem-ipsum-list-bullet (default value: “* “)
Lorem-ipsum-list-item-end (default value: “\n”)
Lorem-ipsum-list-end (default value: “”)
