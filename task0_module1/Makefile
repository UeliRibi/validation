DESTDIR=dist

help:   ## Show this help usage
	@fgrep -h "##" $(MAKEFILE_LIST) | fgrep -v fgrep | sed -e 's/\\$$//' | sed -e 's/##//'

build:  ## Build the website (in Directory dest)
	hugo

clean:  ## Cleans the directory dest)
	rm -r $(DESTDIR)
	
post:   ## Create a new post. Arguments arePOST_NAME and POST_TITLE
	hugo new posts/$(POST_NAME).md


