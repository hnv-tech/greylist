# greylist
Greylist is a stand-alone milter written in C that implements the greylist filtering method.  Greylisting works by assuming that, unlike legitimate MTA, spam engines will not retry sending their junk mail on a temporary error. The filter will always reject mail temporarily on a first attempt, then accept it after some time has elapsed.
