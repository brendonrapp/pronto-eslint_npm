#!/usr/bin/env rake
# frozen_string_literal: true

require 'bundler'
require 'rspec/core/rake_task'

Bundler::GemHelper.install_tasks
RSpec::Core::RakeTask.new(:spec)

task(:default).clear
task default: [:spec]
