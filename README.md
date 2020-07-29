# Ruby code for RabbitMQ tutorials

Here you can find Ruby code examples from
[RabbitMQ tutorials](https://www.rabbitmq.com/getstarted.html).

## Requirements

These tutorials require Ruby 2.2 or later, [Bundler](https://bundler.io/) and [Bunny](http://rubybunny.info) to be installed.

To install Bunny with Bundler, do

``` sh
bundle install
```

The tutorials must be started in the respective subdirectories. Also
config.xml must be adapted to the specfic Rabbitmq installation

## Code

To run [tutorial one: "Hello World!"](https://www.rabbitmq.com/tutorial-one-ruby.html):

``` sh
bundle exec ruby send.rb
bundle exec ruby receive.rb
```

[Tutorial two: Work Queues](https://www.rabbitmq.com/tutorial-two-ruby.html):

``` sh
bundle exec ruby new_task.rb
bundle exec ruby worker.rb
```

[Tutorial three: Publish/Subscribe](https://www.rabbitmq.com/tutorial-three-ruby.html)

``` sh
bundle exec ruby receive_logs.rb
bundle exec ruby emit_log.rb
```

[Tutorial four: Routing](https://www.rabbitmq.com/tutorial-four-ruby.html)

``` sh
bundle exec ruby receive_logs_direct.rb
bundle exec ruby emit_log_direct.rb
```

[Tutorial five: Topics](https://www.rabbitmq.com/tutorial-five-ruby.html)

``` sh
bundle exec ruby receive_logs_topic.rb
bundle exec ruby emit_log_topic.rb
```

[Tutorial six: RPC](https://www.rabbitmq.com/tutorial-six-ruby.html)

``` sh
bundle exec ruby rpc_server.rb
bundle exec ruby rpc_client.rb
```

To learn more, see [Bunny documentation](http://rubybunny.info).