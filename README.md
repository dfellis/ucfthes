--------------------------------------------------------------------------------
UCF Thesis and Dissertation on LATEX 2e (v. 3.0) 
Ivan garibay, igaribay@mail.ucf.edu
--------------------------------------------------------------------------------

                              ** Important ** 

There is some manual processing required to fully comply with the UCF Thesis Editor. 
Please read. If you automate this process I would like to know about it.

To compile you thesis:

START
1) latex paper
2) bibtex paper
3) latex paper

4) Edit the file "paper.out" to include the command "\let\WriteBookmarks\relax"
   and the word "CHAPTER " on the appropriate chapter bookmarks.
   Please see the template file provided "EXAMPLE OF EDITED  paper.out"

5) latex paper
6) dvipdfm paper
END


NOTE: 
The command "\let\WriteBookmarks\relax" included in the "paper.out" file
indicate latex to do not update "paper.out". To recompile:
	A) [If there are no changes in your chapters]
	   To recompile your thesis you can skip the step 4 from above.

	B) [If there are changes in your chapters]
	   To recompile first delete "paper.out", then follow all the steps 1 to 6.

 