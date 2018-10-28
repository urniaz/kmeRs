# kmeRs: The k-mers similarity score matrix package

Package: kmeRs
Title: K-mers similarity score matrix
Version: 1.1.0
Authors@R: person("Rafal", "Urniaz", email = "rafal.urniaz@gmail.com", role = c("aut", "cre"))
Description: Contains tools to calculate DNA similarity score matrix for k length given k-mers 
             vs. all possible k-mers combination. The pairwise similarity score is calculated
             using PAM or BLOSUM substitution matrix; 30, 40, 70, 120, 250 and 62, 45, 50, 62,
             80, 100 matrix versions are available for PAM and BLOSUM, respectively. The results
             are evaluated by global similarity score calculated by Needleman-Wunsch global 
             alignment or Smith-Waterman local alignment. Higher similarity score indicates more 
             similar sequences for BLOSUM and opposite for PAM matrix. 
Depends: R (>= 3.4.0)
License: GPL-3
Encoding: UTF-8
URL: http://github.com/RafalUrniaz/kmeRs
BugReports: http://github.com/RafalUrniaz/kmeRs/issues
LazyData: true
Imports: tcR,
    rDNAse,
    utils,
    stats
RoxygenNote: 6.1.0
Suggests: knitr,
    ape (>= 4.0),
    rmarkdown
VignetteBuilder: knitr

