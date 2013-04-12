# TimeDifference

TimeDifference is the missing Ruby method to calculate difference between two given time. You can do a Ruby time difference in year, month, week, day, hour, minute, and seconds.

## Installation

Add this line to your application's Gemfile:

    gem 'time_difference', git: 'git@github.com:tmlee/time_difference.git'

And then execute:

    $ bundle

## Usage

### Get the time difference in year

start_time = Time.new(2013,1)
end_time = Time.new(2014,1)
TimeDifference.between(start_time, end_time).in_years
=> 1.0

### Get the time difference in year

start_time = Time.new(2013,1)
end_time = Time.new(2014,1)
TimeDifference.between(start_time, end_time).in_months
=> 12.0

### Supported time difference includes

	in_years
	in_months
	in_weeks
	in_days
	in_hours
	in_minutes
	in_seconds
	

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
