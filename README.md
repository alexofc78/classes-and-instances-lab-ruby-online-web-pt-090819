#and this other
class Person
  adele_goldberg = new.Person
  alan_kay = new.Person
end



// ♥ learn

An error occurred while loading spec_helper.
Failure/Error: adele_goldberg = new.Person

NoMethodError:
  undefined method `Person' for #<Person:0x0000000002b84230>
# ./lib/person.rb:2:in `<class:Person>'
# ./lib/person.rb:1:in `<top (required)>'
# ./spec/spec_helper.rb:2:in `require_relative'
# ./spec/spec_helper.rb:2:in `<top (required)>'

An error occurred while loading ./spec/classes_and_instances_spec.rb.
Failure/Error: adele_goldberg = new.Person

NoMethodError:
  undefined method `Person' for #<Person:0x0000000002cb3688>
# ./lib/person.rb:2:in `<class:Person>'
# ./lib/person.rb:1:in `<top (required)>'
# ./spec/spec_helper.rb:2:in `require_relative'
# ./spec/spec_helper.rb:2:in `<top (required)>'
# ./spec/classes_and_instances_spec.rb:1:in `require'
# ./spec/classes_and_instances_spec.rb:1:in `<top (required)>'

An error occurred while loading ./spec/classes_and_instances_spec.rb.
Failure/Error: adele_goldberg = new.Person

NoMethodError:
  undefined method `Person' for #<Person:0x0000000002cb3688>
# ./lib/person.rb:2:in `<class:Person>'
# ./lib/person.rb:1:in `<top (required)>'
# ./spec/spec_helper.rb:2:in `require_relative'
# ./spec/spec_helper.rb:2:in `<top (required)>'
# ./spec/classes_and_instances_spec.rb:1:in `require'
# ./spec/classes_and_instances_spec.rb:1:in `<top (required)>'
No examples found.
No examples found.


Finished in 0.00038 seconds (files took 0.06543 seconds to load)
0 examples, 0 failures, 2 errors occurred outside of examples

Finished in 0.00038 seconds (files took 0.06543 seconds to load)
0 examples, 0 failures, 2 errors occurred outside of examples


[17:55:26] (master) classes-and-instances-lab-ruby-online-web-pt-090819
// ♥
# Classes And Instances Lab Ruby

## Objectives

1. Define new Ruby classes with the `class` keyword.
2. Instantiate instances of a `class`.

## Overview

This lab is all about defining classes and instantiating instances.

## Instructions

Open this lab with `learn open` and run your tests with `learn`.

### 1. Define `Dog` in `lib/dog.rb`

Open `lib/dog.rb` and add a class definition for a `Dog` class.

### 2. Make 3 dogs in `lib/dog.rb`

Under your `Dog` class definition, create three dogs in local variables, `fido`, `snoopy`, and `lassie`.

### 3. Define a `Person` in `lib/person.rb`

Open `lib/person.rb` and add a class definition for a `Person` class.

### 4. Make 2 people in `lib/person.rb`

Under your `Person` class definition, create two people in local variables, `adele_goldberg` and `alan_kay`

When you're done, submit the lab with `learn submit`.

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/classes-and-instances-lab-ruby' title='Classes And Instances Lab Ruby'>Classes And Instances Lab Ruby</a> on Learn.co and start learning to code for free.</p>
