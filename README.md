# opensource
Open Source Intelligence
git push heroku main
heroku ps:scale web=3 queue=2
heroku ps
== web: 'java lib/foobar.jar $PORT'
web.1: up 2013/02/07 18:59:17 (~ 13m ago)
web.2: up 2013/02/07 18:52:08 (~ 20m ago)
web.3: up 2013/02/07 18:31:14 (~ 41m ago)

== queue: `java lib/queue-processor.jar`
queue.1: up 2013/02/07 18:40:48 (~ 32m ago)
queue.2: up 2013/02/07 18:40:48 (~ 32m ago)
heroku config:set ENCRYPTION_KEY=my_secret_launch_codes
Adding config vars and restarting demoapp... done, v14
ENCRYPTION_KEY:     my_secret_launch_codes
heroku releases
== demoapp Releases
v103 Deploy 582fc95  jon@heroku.com   2013/01/31 12:15:35
v102 Deploy 990d916  jon@heroku.com   2013/01/31 12:01:12
heroku releases:rollback v102
Rolling back demoapp... done, v102
heroku releases
== demoapp Releases
v104 Rollback to v102 jon@heroku.com   2013/01/31 14:11:33 (~15s ago)
v103 Deploy 582fc95   jon@heroku.com   2013/01/31 12:15:35
v102 Deploy 990d916   jon@heroku.com   2013/01/31 12:01:12
heroku run bash
Running `bash` attached to terminal... up, run.8963
~ $ ls
heroku addons:create heroku-redis:mini
uri = URI.parse(ENV["REDIS_URL"])
REDIS = Redis.new(:host => uri.host, :port => uri.port, :password => uri.password)
uri = URI.parse(ENV["REDIS_URL"])
REDIS = Redis.new(:host => uri.host, :port => uri.port, :password => uri.password)
