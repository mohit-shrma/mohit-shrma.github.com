base=cv

BUILD_DIR=./tmp
PDF_DIR=./pdf

${base}.pdf: *.tex
	mkdir -p ${BUILD_DIR}
	mkdir -p ${PDF_DIR}
	latexmk -xelatex -pdf ${base} -outdir=${BUILD_DIR} && mv ${BUILD_DIR}/${base}.pdf ${PDF_DIR}

clean:
	rm -f ${BUILD_DIR}/*
		
