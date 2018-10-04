# ConfigurableHttpResponder
It's a full java Web Server which, through configuration only, sends back bespoke HTTP answers based on the incoming HTTP request.

The responses are chosen depending on 2 parameters from the incomming requests : The URL + Http Method.

You can then amend the responses based on the headers of the incoming request or its body. You can also, completly change an answer based on some request parameters, but the syntax is trickier !
