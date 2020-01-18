#makefile for Waseem's resume

waseem_resume.dvi: waseem_resume.xtx
	xelatex waseem_resume.xtx

waseem_resume.ps: waseem_resume.dvi
	dvips -Ppdf -G0 waseem_resume.dvi

waseem_resume.pdf: waseem_resume.ps
	ps2pdf waseem_resume.ps

PDF: waseem_resume.pdf
	xpdf waseem_resume.pdf

