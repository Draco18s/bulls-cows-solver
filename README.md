Bulls and Cows Solver
=====================

Get all the possible answers for Bulls and Cows game, based on the history of guesses in one round.

Web based example can be launched from [https://draco18s.github.io/bulls-cows-solver/index.html](https://draco18s.github.io/bulls-cows-solver/index.html).

Usage
-----

Node

	var bulls_cows_solver = require('bulls-cows-solver');
	var result = bulls_cows_solver([
		{guess:'123', result:'1A2B'},
		{guess:'213', result:'2A1B'},
	]);

Brwoser

	<script type='text/javascript' src='bulls-cows-solver.js'></script>
	<script type='text/javascript'>
		var result = bulls_cows_solver([
			{guess:'123', result:'1A2B'},
			{guess:'213', result:'2A1B'},
		]);
	</script>

