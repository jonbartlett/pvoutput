# PVOutput

A Ruby wrapper around PVOutput [API](http://pvoutput.org/help.html#api).

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/pvoutput`. To experiment with that code, run `bin/console` for an interactive prompt.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'pvoutput'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install pvoutput

## Usage

TODO: Write usage instructions here

## Service Capability

At the time of writing, the PVOutput API consists of the following services.

| Service Name | URL | Implemented |
| ------------ | --- | ----------- |
| [Add Output](http://pvoutput.org/help.html#api-addoutput) | http://pvoutput.org/service/r2/addoutput.jsp | no | 
| [Add Status](http://pvoutput.org/help.html#api-addstatus) | http://pvoutput.org/service/r2/addstatus.jsp | no |
| [Add Batch Output](http://pvoutput.org/help.html#api-addbatchoutput) | http://pvoutput.org/service/r2/addbatchoutput.jsp | no |
| [Add Batch Status](http://pvoutput.org/help.html#api-addbatchstatus) | http://pvoutput.org/service/r2/addbatchstatus.jsp | no |
| [Get Status](http://pvoutput.org/help.html#api-getstatus) | http://pvoutput.org/service/r2/getstatus.jsp | no |
| [Get Statistic](http://pvoutput.org/help.html#api-getstatistic) | http://pvoutput.org/service/r2/getstatistic.jsp | yes |
| [Get System](http://pvoutput.org/help.html#api-getsystem) | http://pvoutput.org/service/r2/getsystem.jsp | no |
| [Get Output](http://pvoutput.org/help.html#api-getoutput) | http://pvoutput.org/service/r2/getoutput.jsp | no |
| [Get Extended](http://pvoutput.org/help.html#api-getextended) | http://pvoutput.org/service/r2/getextended.jsp | no |
| [Get Favourite](http://pvoutput.org/help.html#api-getfavourite) | http://pvoutput.org/service/r2/getfavourite.jsp | no |
| [Get Missing](http://pvoutput.org/help.html#api-getmissing) | http://pvoutput.org/service/r2/getmissing.jsp | no |
| [Get Insolation](http://pvoutput.org/help.html#api-getinsolation) | http://pvoutput.org/service/r2/getinsolation.jsp | no |
| [Delete Status](http://pvoutput.org/help.html#api-deletestatus) | http://pvoutput.org/service/r2/deletestatus.jsp | no |
| [Search](http://pvoutput.org/help.html#api-search) | http://pvoutput.org/service/r2/search.jsp | no |
| [Get Team](http://pvoutput.org/help.html#api-getteam) | http://pvoutput.org/service/r2/getteam.jsp | no |
| [Join Team](http://pvoutput.org/help.html#api-jointeam) | http://pvoutput.org/service/r2/jointeam.jsp | no |
| [Leave Team](http://pvoutput.org/help.html#api-leaveteam) | http://pvoutput.org/service/r2/leaveteam.jsp | no |
| [Get Supply](http://pvoutput.org/help.html#api-getsupply) | http://pvoutput.org/service/r2/getsupply.jsp | no |
| [Register Notification](http://pvoutput.org/help.html#api-registernotification) | http://pvoutput.org/service/r2/registernotification.jsp | no |
| [Deregister Notification](http://pvoutput.org/help.html#api-registernotification) | http://pvoutput.org/service/r2/deregisternotification.jsp | no |

## Rate Limits

The following rate limits applies per API key for all request types -

* 60 requests per hour.
* 300 requests per hour in donation mode.

It is recommended to make requests at least 10 seconds apart.

**via [PVOutput API Documentaion](http://pvoutput.org/help.html#api)**

## Links

* [PVOutput API](http://pvoutput.org/help.html#api)



## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release` to create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

1. Fork it ( https://github.com/[my-github-username]/pvoutput/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
