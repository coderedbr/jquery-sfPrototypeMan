# jquery.sfPrototypeMan

A jQuery plugin for the management of HTML forms generated by Symfony 2 with the [allow_add option](http://symfony.com/doc/current/reference/forms/types/collection.html#allow-add) enabled.

## Installation

Include script *after* the jQuery library

		<script src="/path/to/jquery.sfprototypeman.js"></script>

## Usage

Run
		jQuery().sfPrototypeMan()
to extend Symfony generated forms with collections that ("allow_add" option) offer the ability to add unknown/unlimited number of sub-forms/fields of a certain type

http://symfony.com/doc/current/cookbook/form/form_collections.html#cookbook-form-collections-new-prototype

### Preamble

## Events

You can attach listeners to sfPrototypeMan that will respond events emitted by
third-party code on the nodes handles by sfPrototypeMan.

## Todo

* Emit a change events (container.trigger) on nodes sfPrototypeMan handles
* http://plugins.jquery.com/docs/publish/

<container data-prototype="--markup for new field--">
	<field>
</container>