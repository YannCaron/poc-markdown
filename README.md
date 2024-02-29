<base target="_blank">

# poc-markdown

[link... open it!](https://www.eddymens.com/blog/how-to-make-a-markdown-link-open-in-another-tab)

<a href="http://example.com" target="_blank">https://www.eddymens.com/blog/how-to-make-a-markdown-link-open-in-another-tab</a>

# math
> $$
\begin{align}
A \rightarrow A\alpha | \beta \implies
&A \rightarrow \beta A' \\
&A' \rightarrow \alpha A' | \epsilon
\end{align}
$$

To avoid that, you must modify the grammar to remove the left recursion by replacing it by a right recursion.
> :bulb: Use the replacement formula founded [here](https://www.tutorialspoint.com/what-is-left-recursion-and-how-it-is-eliminated):
> 
> $$
\begin{align}
A \rightarrow A\alpha | \beta \implies
&A \rightarrow \beta A' \\
&A' \rightarrow \alpha A' | \epsilon
\end{align}
$$
