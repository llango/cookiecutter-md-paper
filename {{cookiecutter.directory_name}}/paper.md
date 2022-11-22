---
title: "{{ cookiecutter.title }}"
author: 
{%- for author in cookiecutter.author_full_names_separated_by_commas.split(",") %}
  - {{ author.lstrip() }}
{%- endfor %}
{%- if cookiecutter.double_spacing != "n" or cookiecutter.double_spacing != "n" %}
header-includes:
{%- endif %}
{%- if cookiecutter.double_spacing != "n" %}
  - \usepackage{setspace}
  - \doublespacing
{%- endif %}
{%- if cookiecutter.line_numbers != "n"%}
  - \usepackage[left]{lineno}
  - \linenumbers
{%- endif %}
{%- if cookiecutter.margin_inches != "default" %}
geometry: margin={{cookiecutter.margin_inches}}in
{%- endif %}
{%- if cookiecutter.font_size != "default" %}
fontsize: {{cookiecutter.font_size}}pt
{%- endif %}
{%- if cookiecutter.two_columns != "n" %}
classoption: twocolumn
{%- endif %}
bibliography: bibliography.bib
{%- if cookiecutter.bibliography_style != "Default LaTeX" %}
csl: style.csl
{%- endif %}
{%- if cookiecutter.abstract == "y" %}
{%- if cookiecutter.include_lorem_ipsum != "n" %}
abstract: |
  It is important to take care of the patient, to be followed by the doctor, but it is a time of great pain and suffering.
  Mattis pellentesque id nibh tortor id aquet lectus proin nibh
  Sometimes the earth wants to let it go.
  That is to say that the price of the cartoon has been suspended by the powerful.
  It is now very easy to drink.
  Viverra nibh tomorrow pulvinar mattis now but flatters the free life.
  Id diam maecenas ultricies mi eget mauris pharetra et ultrices.
  The result is sometimes a lot of real estate.
  He wanted the chocolate in the said not to be followed by a was for.
  I do not need to decorate my quiver and ultrice.
  In the previous fear it was said that
{%- else %}
abstract: ""
{%- endif -%}
{%- endif %}
---

{%- if cookiecutter.include_standard_paper_headings != "n" %}

# Introduction

{% if cookiecutter.include_lorem_ipsum != "n" -%}
It's very important to be patient, to be followed by a doctor, but it's a time when it's a big pain and a lot of work [@Lee2018]. Mattis pellentesque id nibh tortor id aquet lectus proin nibh Sometimes the earth wants to let it go. That is to say that the price of the cartoon has been suspended by the powerful. It is now very easy to drink. Viverra nibh tomorrow pulvinar mattis now but flatters the free life. Id diam maecenas ultricies mi eget mauris pharetra et ultrices. The result is sometimes a lot of real estate. He wanted the chocolate in the said not to be followed by a was for. I do not need to decorate my quiver and ultrice. In the previous fear it was said that

The whole life of Mauris ultricies is expected now or There is no need for medical treatment for children. Malsuada kids need to be pregnant with. Homework from the arc of the course of life. Until the basketball players are not members or members of the arc as well. He hung up to adorn his pure throat, but if it was not a lake, he would draw it. Let it be a lot of venomous urn cursing now the chocolate cartoon. One must drink a whole lot of wine. The price of the bronze scepter is great, and the vestibulum has a great deal of interest. The mass of the ugly, but the element of time, but the price of laughter. Integer eget aquet nibh praesent sadis magna. but for that Achieving the advantage of the developer at the expense of the second layer. The cat needs a real estate policy now. For God's sake, no airline mass that. Now it's time for homework. But now that's always a smile on the pregnant rutrum. Throwing football is not easy. The author is not pregnant.

Softly now, but that smile is always pregnant in the Hendrerit. The children of the pulvinar children live in old age and grandchildren. The desire of God to adorn it with a bow of hatred as if it were nothing. And let not the corpse be a lot of laughter. Henderit's pain is a great need. What a cartoon of a football career. Need homework everyone needs a backyard in the arc. And the mountains will be born with feathers and great thrusts. The course of the high school mass of tincidunt dui to decorate the bed is important. For neither the career nor the development of life always. A variety of things will follow. Urna id volutpat lacus laoreet will not be taken care of. Elit scelerisque mauris pellentesque pulvinar pellentesque Neither the time of life than the children nor any other. The mass needs pure pull in the layer. It's a salad and a microwave oven. They sometimes put the food in their mouths.

The ferry boats put a layer of cloud cover and such. Children need a lot of energy. The time investment no expected diesel engine needs to be pregnant. He lived in the street, the vestibulum of the rhoncus is the pellentesque elit ullamcorper dignissim. They live in old age and disease. Elit scelerisque mauris pellentesque pulvinar pellentesque inhabitant morbi trisque. The world in fear vulputate eu. Who laughs more than everyone else? He does not need a great warm-up for football goals. Curabitur gravida arcu ac tortor dignissim convallis aenean. It needs to be followed by trucks with arrows. Pregnant nor the valley from tomorrow. The dyes to decorate the mass need to be pure. And the wretched wretchedness of the whole needs the lorries of the great tribulation present. It is completely expected now or the smile is convenient.

It is sad and necessary that someone should have suspended the pregnancy. The chocolate can be pulled out until the price. The element of life will be taken care of now but he wants to be a member of the football team. How many kids, not even a single one. Let it be said that it will be just until the diam vulputate. For the earth is the element of the arrows of life. Tincidunt propaganda sometimes wants Euismod. I don't need to drink in football. And he invests the vestibule of the bed of the great basketball. A real estate agent. But he would like to adorn the mass of the disease. It is flattering to have a free weekend but to decorate the bow tomorrow. The whole life of the ultricia is now fully expected or the smile is a good cartoon. Who is the author of this book but my vulputate is a lot of fun. The whole of the life of the ultricies is now expected. Even if it's a lot of fun for the fans. Fly fast but pulvinar proin. You need the price of a large bronze quiver and a bed vestibule. Viverra is an easy-to-use outdoor pool. And trigger until and hate. 
{%- endif %}

# Methods

{% if cookiecutter.include_lorem_ipsum != "n" -%}
It is important to take care of the patient, to be followed by the doctor, but it is a time of great pain and suffering. Mattis pellentesque id nibh tortor id aquet lectus proin nibh Sometimes the earth wants to let it go. That is to say that the price of the cartoon has been suspended by the powerful. It is now very easy to drink. Viverra nibh tomorrow pulvinar mattis now but flatters the free life. Id diam maecenas ultricies mi eget mauris pharetra et ultrices. The result is sometimes a lot of real estate. He wanted the chocolate in the said not to be followed by a was for. I do not need to decorate my quiver and ultrice. In the previous fear it was said that

The whole life of Mauris ultricies is expected now or There is no need for medical treatment for children. Malsuada kids need to be pregnant with. Homework from the arc of the course of life. Until the basketball players are not members or members of the arc as well. He hung up to adorn his pure throat, but if it was not a lake, he would draw it. Let it be a lot of venomous urn cursing now the chocolate cartoon. One must drink a whole lot of wine. The price of the bronze scepter is great, and the vestibulum has a great deal of interest. The mass of the ugly, but the element of time, but the price of laughter. Integer eget aquet nibh praesent sadis magna. but for that Achieving the advantage of the developer at the expense of the second layer. The cat needs a real estate policy now. For God's sake, no airline mass that. Now it's time for homework. But now that's always a smile on the pregnant rutrum. Throwing football is not easy. The author is not pregnant.

Softly now, but that smile is always pregnant in the Hendrerit. The children of the pulvinar children live in old age and grandchildren. The desire of God to adorn it with a bow of hatred as if it were nothing. And let not the corpse be a lot of laughter. Henderit's pain is a great need. What a cartoon of a football career. Need homework everyone needs a backyard in the arc. And the mountains will be born with feathers and great thrusts. The course of the high school mass of tincidunt dui to decorate the bed is important. For neither the career nor the development of life always. A variety of things will follow. Urna id volutpat lacus laoreet will not be taken care of. Elit scelerisque mauris pellentesque pulvinar pellentesque Neither the time of life than the children nor any other. The mass needs pure pull in the layer. It's a salad and a microwave oven. They sometimes put the food in their mouths.

The ferry boats put a layer of cloud cover and such. Children need a lot of energy. The time investment no expected diesel engine needs to be pregnant. He lived in the street, the vestibulum of the rhoncus is the pellentesque elit ullamcorper dignissim. They live in old age and disease. Elit scelerisque mauris pellentesque pulvinar pellentesque inhabitant morbi trisque. The world in fear vulputate eu. Who laughs more than everyone else? He does not need a great warm-up for football goals. Curabitur gravida arcu ac tortor dignissim convallis aenean. It needs to be followed by trucks with arrows. Pregnant nor the valley from tomorrow. The dyes to decorate the mass need to be pure. And the wretched wretchedness of the whole needs the lorries of the great tribulation present. It is completely expected now or the smile is convenient.

It is sad and necessary that someone should have suspended the pregnancy. The chocolate can be pulled out until the price. The element of life will be taken care of now but he wants to be a member of the football team. How many kids, not even a single one. Let it be said that it will be just until the diam vulputate. For the earth is the element of the arrows of life. Tincidunt propaganda sometimes wants Euismod. I don't need to drink in football. And he invests the vestibule of the bed of the great basketball. A real estate agent. But he would like to adorn the mass of the disease. It is flattering to have a free weekend but to decorate the bow tomorrow. The whole life of the ultricia is now fully expected or the smile is a good cartoon. Who is the author of this book but my vulputate is a lot of fun. The whole of the life of the ultricies is now expected. Even if it's a lot of fun in the soft. Fly fast but pulvinar proin. You need the price of a large bronze quiver and a bed vestibule. Viverra is an easy-to-use outdoor pool. And trigger until and hate. 
{%- endif %}

# Results

{% if cookiecutter.include_lorem_ipsum != "n" -%}
It is important to take care of the patient, to be followed by the doctor, but it is a time of great pain and suffering. Mattis pellentesque id nibh tortor id aquet lectus proin nibh Sometimes the earth wants to let it go. That is to say that the price of the cartoon has been suspended by the powerful. It is now very easy to drink. Viverra nibh tomorrow pulvinar mattis now but flatters the free life. Id diam maecenas ultricies mi eget mauris pharetra et ultrices. The result is sometimes a lot of real estate. He wanted the chocolate in the said not to be followed by a was for. I do not need to decorate my quiver and ultrice. In the previous fear it was said that

The whole life of Mauris ultricies is expected now or There is no need for medical treatment for children. Malsuada kids need to be pregnant with. Homework from the arc of the course of life. Until the basketball players are not members or members of the arc as well. He hung up to adorn his pure throat, but if it was not a lake, he would draw it. Let it be a lot of venomous urn cursing now the chocolate cartoon. One must drink a whole lot of wine. The price of the bronze scepter is great, and the vestibulum has a great deal of interest. The mass of the ugly, but the element of time, but the price of laughter. Integer eget aquet nibh praesent sadis magna. but for that Achieving the advantage of the developer at the expense of the second layer. The cat needs a real estate policy now. For God's sake, no airline mass that. Now it's time for homework. But now that's always a smile on the pregnant rutrum. Throwing football is not easy. The author is not pregnant.

Softly now, but that smile is always pregnant in the Hendrerit. The children of the pulvinar children live in old age and grandchildren. The desire of God to adorn it with a bow of hatred as if it were nothing. And let not the corpse be a lot of laughter. Henderit's pain is a great need. What a cartoon of a football career. Need homework everyone needs a backyard in the arc. And the mountains will be born with feathers and great thrusts. The course of the high school mass of tincidunt dui to decorate the bed is important. For neither the career nor the development of life always. A variety of things will follow. Urna id volutpat lacus laoreet will not be taken care of. Elit scelerisque mauris pellentesque pulvinar pellentesque Neither the time of life than the children nor any other. The mass needs pure pull in the layer. It's a salad and a microwave oven. They sometimes put the food in their mouths.

The ferry boats put a layer of cloud cover and such. Children need a lot of energy. The time investment no expected diesel engine needs to be pregnant. He lived in the street, the vestibulum of the rhoncus is the pellentesque elit ullamcorper dignissim. They live in old age and disease. Elit scelerisque mauris pellentesque pulvinar pellentesque inhabitant morbi trisque. The world in fear vulputate eu. Who laughs more than everyone else? He does not need a great warm-up for football goals. Curabitur gravida arcu ac tortor dignissim convallis aenean. It needs to be followed by trucks with arrows. Pregnant nor the valley from tomorrow. The dyes to decorate the mass need to be pure. And the wretched wretchedness of the whole needs the lorries of the great tribulation present. It is completely expected now or the smile is convenient.

It is sad and necessary that someone should have suspended the pregnancy. The chocolate can be pulled out until the price. The element of life will be taken care of now but he wants to be a member of the football team. How many kids, not even a single one. Let it be said that it will be just until the diam vulputate. For the earth is the element of the arrows of life. Tincidunt propaganda sometimes wants Euismod. I don't need to drink in football. And he invests the vestibule of the bed of the great basketball. A real estate agent. But he would like to adorn the mass of the disease. It is flattering to have a free weekend but to decorate the bow tomorrow. The whole life of the ultricia is now fully expected or the smile is a good cartoon. Who is the author of this book but my vulputate is a lot of fun. The whole of the life of the ultricies is now expected. Even if it's a lot of fun in the soft. Fly fast but pulvinar proin. You need the price of a large bronze quiver and a bed vestibule. Viverra is an easy-to-use outdoor pool. And trigger until and hate. 
{%- endif %}

# Discussion

{% if cookiecutter.include_lorem_ipsum != "n" -%}
 It is important to take care of the patient, to be followed by the doctor, but it is a time of great pain and suffering. Mattis pellentesque id nibh tortor id aquet lectus proin nibh Sometimes the earth wants to let it go. That is to say that the price of the cartoon has been suspended by the powerful. It is now very easy to drink. Viverra nibh tomorrow pulvinar mattis now but flatters the free life. Id diam maecenas ultricies mi eget mauris pharetra et ultrices. The result is sometimes a lot of real estate. He wanted the chocolate in the said not to be followed by a was for. I do not need to decorate my quiver and ultrice. In the previous fear it was said that

The whole life of Mauris ultricies is expected now or There is no need for medical treatment for children. Malsuada kids need to be pregnant with. Homework from the arc of the course of life. Until the basketball players are not members or members of the arc as well. He hung up to adorn his pure throat, but if it was not a lake, he would draw it. Let it be a lot of venomous urn cursing now the chocolate cartoon. One must drink a whole lot of wine. The price of the bronze scepter is great, and the vestibulum has a great deal of interest. The mass of the ugly, but the element of time, but the price of laughter. Integer eget aquet nibh praesent sadis magna. but for that Achieving the advantage of the developer at the expense of the second layer. The cat needs a real estate policy now. For God's sake, no airline mass that. Now it's time for homework. But now that's always a smile on the pregnant rutrum. Throwing football is not easy. The author is not pregnant.

Softly now, but that smile is always pregnant in the Hendrerit. The children of the pulvinar children live in old age and grandchildren. The desire of God to adorn it with a bow of hatred as if it were nothing. And let not the corpse be a lot of laughter. Henderit's pain is a great need. What a cartoon of a football career. Need homework everyone needs a backyard in the arc. And the mountains will be born with feathers and great thrusts. The course of the high school mass of tincidunt dui to decorate the bed is important. For neither the career nor the development of life always. A variety of things will follow. Urna id volutpat lacus laoreet will not be taken care of. Elit scelerisque mauris pellentesque pulvinar pellentesque Neither the time of life than the children nor any other. The mass needs pure pull in the layer. It's a salad and a microwave oven. They sometimes put the food in their mouths.

The ferry boats put a layer of cloud cover and such. Children need a lot of energy. The time investment no expected diesel engine needs to be pregnant. He lived in the street, the vestibulum of the rhoncus is the pellentesque elit ullamcorper dignissim. They live in old age and disease. Elit scelerisque mauris pellentesque pulvinar pellentesque inhabitant morbi trisque. The world in fear vulputate eu. Who laughs more than everyone else? He does not need a great warm-up for football goals. Curabitur gravida arcu ac tortor dignissim convallis aenean. It needs to be followed by trucks with arrows. Pregnant nor the valley from tomorrow. The dyes to decorate the mass need to be pure. And the wretched wretchedness of the whole needs the lorries of the great tribulation present. It is completely expected now or the smile is convenient.

It is sad and necessary that someone should have suspended the pregnancy. The chocolate can be pulled out until the price. The element of life will be taken care of now but he wants to be a member of the football team. How many kids, not even a single one. Let it be said that it will be just until the diam vulputate. For the earth is the element of the arrows of life. Tincidunt propaganda sometimes wants Euismod. I don't need to drink in football. And he invests the vestibule of the bed of the great basketball. A real estate agent. But he would like to adorn the mass of the disease. It is flattering to have a free weekend but to decorate the bow tomorrow. The whole life of the ultricia is now fully expected or the smile is a good cartoon. Who is the author of this book but my vulputate is a lot of fun. The whole of the life of the ultricies is now expected. Even if it's a lot of fun in the soft. Fly fast but pulvinar proin. You need the price of a large bronze quiver and a bed vestibule. Viverra is an easy-to-use outdoor pool. And trigger until and hate. 
{%- endif %}
{%- endif %}

# Reference
