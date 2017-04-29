# LaTeX Report for CPE 631
## Files
[cpe631.tex](https://github.com/ashtonchase/cpe631_report/blob/master/cpe631.tex) is the source file for the report.

[cpe631.bib](https://github.com/ashtonchase/cpe631_report/blob/master/cpe631.bib) is the bibliography file required.

[IEEEtran.cls](https://github.com/ashtonchase/cpe631_report/blob/master/IEEEtran.cls) is the IEEE class file used for formatting.


## Support
Add the following to your ```~/.emacs``` file to use pdflatex instead of plain latex:

```
(custom-set-variables
 ;; custom-set-variables was added by Custom.
 ;; If you edit it by hand, you could mess it up, so be careful.
 ;; Your init file should contain only one such instance.
 ;; If there is more than one, they won't work right.                     
 '(latex-run-command "pdflatex"))
(custom-set-faces
 ;; custom-set-faces was added by Custom.                                                                                     
 ;; If you edit it by hand, you could mess it up, so be careful.                                                             
 ;; Your init file should contain only one such instance.                                                                     
 ;; If there is more than one, they won't work right.                                                                        
 )
```
