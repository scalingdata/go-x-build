usage: FORCE
	# See Makefile targets.
	exit 1

FORCE:

upload: FORCE
	go install github.com/scalingdata/go-x-build/cmd/upload
	upload --verbose --gzip --file=run-builder-darwin-10_8.sh -cacheable=false -public=true go-builder-data/run-builder-darwin-10_8.gz
