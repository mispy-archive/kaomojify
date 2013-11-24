# kaomojify (o^_^)o

This little program downloads your Twitter history, runs a Bayes classifier against it trained with a set of emotions, compares the recent emotional state to the average, and then appends an appropriate kaomoji to your name.

### Prerequisites

[Ruby 1.9.3](https://www.ruby-lang.org/en/) and the [bundler gem](http://bundler.io/)

### Usage

1. Clone the repository
2. Run `bundle install`
3. Move `config.rb.sample` to `config.rb`
4. Edit `config.rb` with your details
5. Run `kaomojify`

You may also want to tune the default training dataset to your particular standards of expressive cuteness by editing `emotions.tsv`
