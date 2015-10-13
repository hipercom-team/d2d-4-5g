# Cedric Adjih - Inria - Oct 2015

NAME?=adjih

generate:
	./sitetool

copy: generate
	cp -av ../generated/* ../current

upload:
	scp -r ../current/* ${NAME}@scm.gforge.inria.fr:/home/groups/d2d-4-5g/htdocs
