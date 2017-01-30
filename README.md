# tv-maze

## Usage

´´´ js

var tvmaze = require('tv-maze')

var client = tv.createClient()

client.shows(function (err, shows) {
	// do something shows...
})

client.search('lost', function(err, shows) {
	// do something shows...
})
´´´
