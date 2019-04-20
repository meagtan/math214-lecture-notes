Some general rules for typesetting. Please read this file carefully: if there
is anything which you find unclear, you should ask for clarifications.

1. Before starting to work on the template file I provided, please take some
time and read the LaTeX tutorial ltxprimer-1.0.pdf, especially the sections 
on typesetting mathematics and the following.

2. Also, take a look at the structure of the template file and understand
the provided macros.

3. As a general rule, use as much the LaTeX style format and not improvised
format for spacing, subsections, and so on. For this, please first read
carefully the tutorial, or other more comprehensive tutorials. For example, do
not use your own numbering: let LaTeX do the automatic numbering.

4. Please use \begin{theorem} ... \end{theorem}, or the other suitable
statements forms, like \begin{fact} ... \end{fact}.

5. For proofs use \begin{proof} ... \end{proof}. Some proofs in the manuscript 
are divided in steps by using dots. You may use $\bullet$ for these, 
or may use steps: \textbf{Step 1}, \textbf{Step 2}, etc.

6. There are some macros in the Preamble part, please take a look at them and
use them if the corresponding letters are used (usually, black bold characters
and caligraphic). Please do not use, unless really necessary, 
your own macros. In case you think that it is absolutely necessary 
to make your own macros, insert them in a special region, 
for instance %%% My Own Macros, of the Preamble (before the \begin{document} 
command} and let me know.

7. If a group of words in underlined in the manuscript, if it is not a title
of a section or subsection, you have to write it in italics with \emph{...},
not by underlining.

8. There are some graphics in the manuscript. In this case, you may need the
package graphics.sty or graphicx.sty, but it is not really necessary to
draw the graphics. Also, there are a few diagrams that you may want to
draw. In either cases you have to draw may attention about this.

9. There may be errors in my manuscript, like typos, or mistakes in
calculations or reasoning: if you see such an error let me know
and I will inspect again that part of the manuscript.

10. For displayed equations use \begin{equation*} ... \end{equation*} and not
the obsolete versions $$ ... $$.

11. In the manuscript I underlined words that should be written in italic, by
using the environment \emph{...}.

12. There are symbols for the universal quantifier and for the existential 
quantifier, but I prefer to write the words: for any, there exists.

13. If you want to use cross citation labels you should use letters, not
numbers.

14. Do not change the general layout that comes with the template file.

15. Finally, if there are things that you are not sure about, it is better to
ask me before doing, since you may have to redo it.

16. When finished, the group representative should e-mail to me the source
file, ChapterNN.tex, after you make sure that there are no more errors 
during the compilation process.
