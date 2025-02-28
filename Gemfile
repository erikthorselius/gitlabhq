source "https://rubygems.org"

gem 'rails', '4.2.6'
gem 'rails-deprecated_sanitizer', '~> 1.0.3'

# Responders respond_to and respond_with
gem 'responders', '~> 2.0'

# Specify a sprockets version due to increased performance
# See https://gitlab.com/gitlab-org/gitlab-ce/issues/6069
gem 'sprockets', '~> 3.6.0'

# Default values for AR models
gem "default_value_for", "~> 3.0.0"

# Supported DBs
gem "mysql2", '~> 0.3.16', group: :mysql
gem "pg", '~> 0.18.2', group: :postgres

# Authentication libraries
gem 'devise',                 '~> 3.5.4'
gem 'devise-async',           '~> 0.9.0'
gem 'doorkeeper',             '~> 2.2.0'
gem 'omniauth',               '~> 1.3.1'
gem 'omniauth-auth0',         '~> 1.4.1'
gem 'omniauth-azure-oauth2',  '~> 0.0.6'
gem 'omniauth-bitbucket',     '~> 0.0.2'
gem 'omniauth-cas3',          '~> 1.1.2'
gem 'omniauth-facebook',      '~> 3.0.0'
gem 'omniauth-github',        '~> 1.1.1'
gem 'omniauth-gitlab',        '~> 1.0.0'
gem 'omniauth-google-oauth2', '~> 0.2.0'
gem 'omniauth-kerberos',      '~> 0.3.0', group: :kerberos
gem 'omniauth-saml',          '~> 1.5.0'
gem 'omniauth-shibboleth',    '~> 1.2.0'
gem 'omniauth-twitter',       '~> 1.2.0'
gem 'omniauth_crowd',         '~> 2.2.0'
gem 'rack-oauth2',            '~> 1.2.1'

# Spam and anti-bot protection
gem 'recaptcha', require: 'recaptcha/rails'
gem 'akismet', '~> 2.0'

# Two-factor authentication
gem 'devise-two-factor', '~> 2.0.0'
gem 'rqrcode-rails3', '~> 0.1.7'
gem 'attr_encrypted', '~> 1.3.4'

# Browser detection
gem "browser", '~> 1.0.0'

# Extracting information from a git repository
# Provide access to Gitlab::Git library
gem "gitlab_git", '~> 10.0'

# LDAP Auth
# GitLab fork with several improvements to original library. For full list of changes
# see https://github.com/intridea/omniauth-ldap/compare/master...gitlabhq:master
gem 'gitlab_omniauth-ldap', '~> 1.2.1', require: "omniauth-ldap"

# Git Wiki
# Required manually in config/initializers/gollum.rb to control load order
gem 'gollum-lib', '~> 4.1.0', require: false
gem 'gollum-rugged_adapter', '~> 0.4.2', require: false

# Language detection
gem "github-linguist", "~> 4.7.0", require: "linguist"

# API
gem 'grape',        '~> 0.13.0'
gem 'grape-entity', '~> 0.4.2'
gem 'rack-cors',    '~> 0.4.0', require: 'rack/cors'

# Pagination
gem "kaminari", "~> 0.16.3"

# HAML
gem "haml-rails", '~> 0.9.0'

# Files attachments
gem "carrierwave", '~> 0.10.0'

# Drag and Drop UI
gem 'dropzonejs-rails', '~> 0.7.1'

# for aws storage
gem "fog", "~> 1.36.0"
gem "unf", '~> 0.1.4'

# Authorization
gem "six", '~> 0.2.0'

# Seed data
gem "seed-fu", '~> 2.3.5'

# Markdown and HTML processing
gem 'html-pipeline', '~> 1.11.0'
gem 'task_list',     '~> 1.0.2', require: 'task_list/railtie'
gem 'github-markup', '~> 1.3.1'
gem 'redcarpet',     '~> 3.3.3'
gem 'RedCloth',      '~> 4.2.9'
gem 'rdoc',          '~>3.6'
gem 'org-ruby',      '~> 0.9.12'
gem 'creole',        '~> 0.5.0'
gem 'wikicloth',     '0.8.1'
gem 'asciidoctor',   '~> 1.5.2'
gem 'rouge',         '~> 1.10.1'

# See https://groups.google.com/forum/#!topic/ruby-security-ann/aSbgDiwb24s
# and https://groups.google.com/forum/#!topic/ruby-security-ann/Dy7YiKb_pMM
gem 'nokogiri', '~> 1.6.7', '>= 1.6.7.2'

# Diffs
gem 'diffy', '~> 3.0.3'

# Application server
group :unicorn do
  gem "unicorn", '~> 4.9.0'
  gem 'unicorn-worker-killer', '~> 0.4.2'
end

# State machine
gem "state_machines-activerecord", '~> 0.3.0'
# Run events after state machine commits
gem 'after_commit_queue'

# Issue tags
gem 'acts-as-taggable-on', '~> 3.4'

# Background jobs
gem 'sinatra', '~> 1.4.4', require: nil
gem 'sidekiq', '~> 4.0'
gem 'sidekiq-cron', '~> 0.4.0'
gem 'redis-namespace'

# HTTP requests
gem "httparty", '~> 0.13.3'

# Colored output to console
gem "colorize", '~> 0.7.0'

# GitLab settings
gem 'settingslogic', '~> 2.0.9'

# Misc

gem 'version_sorter', '~> 2.0.0'

# Cache
gem "redis-rails", '~> 4.0.0'

# Redis
gem 'redis', '~> 3.2'
gem 'connection_pool', '~> 2.0'

# Campfire integration
gem 'tinder', '~> 1.10.0'

# HipChat integration
gem 'hipchat', '~> 1.5.0'

# Flowdock integration
gem "gitlab-flowdock-git-hook", "~> 1.0.1"

# Gemnasium integration
gem "gemnasium-gitlab-service", "~> 0.2"

# Slack integration
gem "slack-notifier", "~> 1.2.0"

# Asana integration
gem 'asana', '~> 0.4.0'

# FogBugz integration
gem 'ruby-fogbugz', '~> 0.2.1'

# d3
gem 'd3_rails', '~> 3.5.0'

#cal-heatmap
gem 'cal-heatmap-rails', '~> 3.5.0'

# underscore-rails
gem "underscore-rails", "~> 1.8.0"

# Sanitize user input
gem "sanitize", '~> 2.0'
gem 'babosa', '~> 1.0.2'

# Sanitizes SVG input
gem "loofah", "~> 2.0.3"

# Protect against bruteforcing
gem "rack-attack", '~> 4.3.1'

# Ace editor
gem 'ace-rails-ap', '~> 2.0.1'

# Keyboard shortcuts
gem 'mousetrap-rails', '~> 1.4.6'

# Detect and convert string character encoding
gem 'charlock_holmes', '~> 0.7.3'

gem "sass-rails", '~> 5.0.0'
gem "coffee-rails", '~> 4.1.0'
gem "uglifier", '~> 2.7.2'
gem 'turbolinks', '~> 2.5.0'
gem 'jquery-turbolinks', '~> 2.1.0'

gem 'addressable',        '~> 2.3.8'
gem 'bootstrap-sass',     '~> 3.3.0'
gem 'font-awesome-rails', '~> 4.2'
gem 'gitlab_emoji',       '~> 0.3.0'
gem 'gon',                '~> 6.0.1'
gem 'jquery-atwho-rails', '~> 1.3.2'
gem 'jquery-rails',       '~> 4.0.0'
gem 'jquery-scrollto-rails', '~> 1.4.3'
gem 'jquery-ui-rails',    '~> 5.0.0'
gem 'raphael-rails',      '~> 2.1.2'
gem 'request_store',      '~> 1.3.0'
gem 'select2-rails',      '~> 3.5.9'
gem 'virtus',             '~> 1.0.1'
gem 'net-ssh',            '~> 3.0.1'

# Sentry integration
gem 'sentry-raven', '~> 0.15'

gem 'premailer-rails', '~> 1.9.0'

# Metrics
group :metrics do
  gem 'allocations', '~> 1.0', require: false, platform: :mri
  gem 'method_source', '~> 0.8', require: false
  gem 'influxdb', '~> 0.2', require: false
end

group :development do
  gem "foreman"
  gem 'brakeman', '~> 3.2.0', require: false

  gem "annotate", "~> 2.7.0"
  gem "letter_opener", '~> 1.1.2'
  gem 'quiet_assets', '~> 1.0.2'
  gem 'rerun', '~> 0.11.0'
  gem 'bullet', require: false
  gem 'rblineprof', platform: :mri, require: false
  gem 'web-console', '~> 2.0'

  # Better errors handler
  gem 'better_errors', '~> 1.0.1'
  gem 'binding_of_caller', '~> 0.7.2'

  # Docs generator
  gem "sdoc", '~> 0.3.20'

  # thin instead webrick
  gem 'thin', '~> 1.6.1'
end

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'pry-rails'

  gem 'awesome_print', '~> 1.2.0', require: false
  gem 'fuubar', '~> 2.0.0'

  gem 'database_cleaner',   '~> 1.4.0'
  gem 'factory_girl_rails', '~> 4.6.0'
  gem 'rspec-rails',        '~> 3.3.0'
  gem 'rspec-retry'
  gem 'spinach-rails',      '~> 0.2.1'
  gem 'spinach-rerun-reporter', '~> 0.0.2'

  # Prevent occasions where minitest is not bundled in packaged versions of ruby (see #3826)
  gem 'minitest', '~> 5.7.0'

  # Generate Fake data
  gem 'ffaker', '~> 2.0.0'

  gem 'capybara',            '~> 2.6.2'
  gem 'capybara-screenshot', '~> 1.0.0'
  gem 'poltergeist',         '~> 1.9.0'

  gem 'teaspoon', '~> 1.1.0'
  gem 'teaspoon-jasmine', '~> 2.2.0'

  gem 'spring',                   '~> 1.7.0'
  gem 'spring-commands-rspec',    '~> 1.0.4'
  gem 'spring-commands-spinach',  '~> 1.1.0'
  gem 'spring-commands-teaspoon', '~> 0.0.2'

  gem 'rubocop', '~> 0.38.0', require: false
  gem 'scss_lint', '~> 0.47.0', require: false
  gem 'coveralls',  '~> 0.8.2', require: false
  gem 'simplecov', '~> 0.11.0', require: false
  gem 'flog', require: false
  gem 'flay', require: false
  gem 'bundler-audit', require: false

  gem 'benchmark-ips', require: false
end

group :test do
  gem 'shoulda-matchers', '~> 2.8.0', require: false
  gem 'email_spec', '~> 1.6.0'
  gem 'webmock', '~> 1.21.0'
  gem 'test_after_commit', '~> 0.4.2'
  gem 'sham_rack'
end

group :production do
  gem "gitlab_meta", '7.0'
end

gem "newrelic_rpm", '~> 3.14'

gem 'octokit', '~> 3.8.0'

gem "mail_room", "~> 0.6.1"

gem 'email_reply_parser', '~> 0.5.8'

## CI
gem 'activerecord-deprecated_finders', '~> 1.0.3'
gem 'activerecord-session_store', '~> 0.1.0'
gem "nested_form", '~> 0.3.2'

# OAuth
gem 'oauth2', '~> 1.0.0'

# Soft deletion
gem "paranoia", "~> 2.0"
