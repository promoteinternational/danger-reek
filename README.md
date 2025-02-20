# danger-reek

[![Build Status](https://badgen.net/travis/blooper05/danger-reek?icon=travis)](https://travis-ci.com/blooper05/danger-reek)
[![Dependency Status](https://api.dependabot.com/badges/status?host=github&repo=blooper05/danger-reek)](https://dependabot.com)
[![Maintainability](https://badgen.net/codeclimate/maintainability/blooper05/danger-reek?icon=codeclimate)](https://codeclimate.com/github/blooper05/danger-reek)
[![Coverage](https://badgen.net/codeclimate/coverage/blooper05/danger-reek?icon=codeclimate)](https://codeclimate.com/github/blooper05/danger-reek)
[![Version](https://badgen.net/rubygems/v/danger-reek?icon=ruby)](https://rubygems.org/gems/danger-reek)
[![License](https://badgen.net/github/license/blooper05/danger-reek?icon=github)](https://github.com/blooper05/danger-reek/blob/master/LICENSE)

A [Danger](https://rubygems.org/gems/danger) plugin for [Reek](https://rubygems.org/gems/reek).

## Installation

    $ gem install danger-reek

## Usage

### reek

Lints Ruby files via [Reek](https://rubygems.org/gems/reek).
Results are sent as inline comments.

<blockquote>Running Reek
  <pre>
# Runs Reek on modified and added files in the PR
reek.lint</pre>
</blockquote>

#### Methods

`lint` - Runs Ruby files through Reek.

## Development

1. Clone this repo
2. Run `bundle install` to setup dependencies.
3. Run `bundle exec rake spec` to run the tests.
4. Use `bundle exec guard` to automatically have tests run as you make changes.
5. Make your changes.
