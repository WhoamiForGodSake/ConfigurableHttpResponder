# ConfigurableHttpResponder
It's a full java Web Server which, through configuration only, sends back bespoke HTTP answers based on the incoming HTTP request.

The responses are chosen depending on 3 parameters from the incomming requests : The URL + Http Method + A random number between 0-99.

The random number allows you to define, for exemple a percentage of error response you'll send back.

You can then amend the responses, delay them based on the headers of the incoming request or its body. You can also, completly change an answer based on some request parameters, but the syntax is trickier !

For a detailled explanation, download the Dokuwiki file, unzip it and run run.cmd as an administrator (for windows), for other OS, I'm sure you'll find a way ! Please note that you might have to modify the path in run.cmd depending on your OS configuration. If needed, the administrator user/password is admin/manage.

For a quick video of a basic installation with simple configuration : Download *Video_ConfigurableHttpResponder_Basic_Install_and_conf.7z*.
