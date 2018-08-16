# Rubocop Defaults

This gem just has my rubocop defaults for easy inclusion in other projects.

## Usage

Add this line to your application's Gemfile (to use the gem in another gem, put the `gem` call in `group :development` so that it is not added as a dependency when the gem is installed):

```ruby
gem 'rubocop_defaults', github: 'dvandersluis/rubocop_defaults'
```

Add the following to `.rubocop.yml`

```yaml
inherit_gem:
  rubocop_defaults: .rubocop.yml
  
inherit_mode:
  merge:
    - Exclude
```
