# Rubocop Defaults

This gem just has my rubocop defaults for easy inclusion in other projects.

## Usage

Add this line to your application's Gemfile:

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
