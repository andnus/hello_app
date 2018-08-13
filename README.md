# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

	ruby 2.3.1p112 (2016-04-26) [x86_64-linux-gnu]   default									 
	gem 2.5.2.1

	Rails 5.1.4							sudo gem install rails -v 5.1.4


* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* Project create         rails _5.1.4_ new hello_app

`-- hello_app
    |-- Gemfile
    |-- README.md
    |-- Rakefile
    |-- app
    |   |-- assets
    |   |   |-- config
    |   |   |   `-- manifest.js
    |   |   |-- images
    |   |   |-- javascripts
    |   |   |   |-- application.js
    |   |   |   |-- cable.js
    |   |   |   `-- channels
    |   |   `-- stylesheets
    |   |       `-- application.css
    |   |-- channels
    |   |   `-- application_cable
    |   |       |-- channel.rb
    |   |       `-- connection.rb
    |   |-- controllers
    |   |   |-- application_controller.rb
    |   |   `-- concerns
    |   |-- helpers
    |   |   `-- application_helper.rb
    |   |-- jobs
    |   |   `-- application_job.rb
    |   |-- mailers
    |   |   `-- application_mailer.rb
    |   |-- models
    |   |   |-- application_record.rb
    |   |   `-- concerns
    |   `-- views
    |       `-- layouts
    |           |-- application.html.erb
    |           |-- mailer.html.erb
    |           `-- mailer.text.erb
    |-- bin
    |   |-- bundle
    |   |-- rails
    |   |-- rake
    |   |-- setup
    |   |-- update
    |   `-- yarn
    |-- config
    |   |-- application.rb
    |   |-- boot.rb
    |   |-- cable.yml
    |   |-- database.yml
    |   |-- environment.rb
    |   |-- environments
    |   |   |-- development.rb
    |   |   |-- production.rb
    |   |   `-- test.rb
    |   |-- initializers
    |   |   |-- application_controller_renderer.rb
    |   |   |-- assets.rb
    |   |   |-- backtrace_silencers.rb
    |   |   |-- cookies_serializer.rb
    |   |   |-- filter_parameter_logging.rb
    |   |   |-- inflections.rb
    |   |   |-- mime_types.rb
    |   |   `-- wrap_parameters.rb
    |   |-- locales
    |   |   `-- en.yml
    |   |-- puma.rb
    |   |-- routes.rb
    |   |-- secrets.yml
    |   `-- spring.rb
    |-- config.ru
    |-- db
    |   `-- seeds.rb
    |-- lib
    |   |-- assets
    |   `-- tasks
    |-- log
    |-- package.json
    |-- public
    |   |-- 404.html
    |   |-- 422.html
    |   |-- 500.html
    |   |-- apple-touch-icon-precomposed.png
    |   |-- apple-touch-icon.png
    |   |-- favicon.ico
    |   `-- robots.txt
    |-- test
    |   |-- application_system_test_case.rb
    |   |-- controllers
    |   |-- fixtures
    |   |   `-- files
    |   |-- helpers
    |   |-- integration
    |   |-- mailers
    |   |-- models
    |   |-- system
    |   `-- test_helper.rb
    |-- tmp
    |   `-- cache
    |       `-- assets
    `-- vendor

	文件/文件夹		作用

	app/ 			应用的核心文件,包含模型、视图、控制器和辅助方法
	app/assets 	应用的静态资源文件,例如层叠样式表(CSS)、JavaScript 文件和图像
	bin/ 		可执行的二进制文件
	config/ 	应用的配置
	db/ 		数据库文件
	doc/ 		应用的文档
	lib/ 		代码库模块文件
	lib/assets  代码库的静态资源文件,例如层叠样式表(CSS)、JavaScript 文件和图
	像
	log/ 		应用的日志文件
	public/ 	公共(如浏览器)可访问的文件,例如错误页面
	bin/rails 	生成代码、打开终端会话或启动本地服务器的程序
	test/ 		应用的测试
	tmp/ 		临时文件
	vendor/ 		第三方代码,例如插件和 gem
	vendor/assets 第三方静态资源文件,例如层叠样式表(CSS)、JavaScript 文件和图像
	README.md 	应用简介
	Rakefile 	使用 rake 命令执行的实用任务
	Gemfile 	应用所需的 gem
	Gemfile.lock gem 列表,确保这个应用的副本使用相同版本的 gem
	config.ru Rack 中间件的配置文件
	.gitignore Git 忽略的文件模式

* ...
