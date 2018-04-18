all: skeleton.Rmd
	Rscript -e "rmarkdown::render('skeleton.Rmd')"
	
clean: 
	-rm skeleton.tex skeleton.pdf
	-rm -rf skeleton_cache figures
	