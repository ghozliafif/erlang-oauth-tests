Unit tests for erlang-oauth (http://github.com/tim/erlang-oauth).

If you have erlang-oauth sitting next to erlang-oauth-tests then you
can just run "make" to compile and run the tests (don't forget to compile
erlang-oauth beforehand).

Alternatively you can use rebar to compile and run the tests against a
specific version of erlang-oauth. By default this runs against the master
branch of github.com/tim/erlang-oauth, but you can specify an alternate
version by editing the rebar.config file. Don't forget to "rebar get-deps"
and "rebar compile" before running "rebar eunit".
