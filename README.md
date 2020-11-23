#Little script to search for MCP mapping names

Before using download srgs and mappings:
	mcp -U -s		downloads mappings for all stable branches
	mcp -D			downloads srgs up to 1.12.2 version

Options:
	-s	search on stable branch
	-u	seatch on snapshots branch
	-b	search on custom branch
	-f	search for field
	-m	search for method
	-p	search for parameter
	-v	minecraft version
	-V	mappings version
	-U	update mappings
	-P	purge branch
	-F	don't prompt for confirmation
	-g	return found files list for manual greping
	-D	download srgs
	-R	include additional information
	-L	include less information
	-w	grep whole words
	-i	grep case insensitive

Examples:
	mcp -f field_000000_a
