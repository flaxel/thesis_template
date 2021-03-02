# Template for a thesis

[![build](https://github.com/flaxel/thesis_template/workflows/build/badge.svg)](https://github.com/flaxel/thesis_template/actions)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/flaxel/thesis_template)](https://github.com/flaxel/thesis_template/releases)
[![GitHub license](https://img.shields.io/github/license/flaxel/thesis_template)](https://github.com/flaxel/thesis_template/blob/master/LICENSE)

This is an easy template for any thesis.

## Getting Started

You can click on the "[Use this template](https://github.com/flaxel/thesis_template/generate)" button to create a new repository with this template. After that you have a repository with the following structure:

* 00_definitions: all configuration files
* 01_metadata: all extra files
* 02_introduction: opening words
* 03_content: main part of the thesis
* 04_finishing: summary and result of the thesis
* 05_resources: all resources like images, ...

At the end you must only change the variables in the [00_definitions/variables.tex](./00_definitions/variables.tex) file. In addition, there are configurations for the [actions in GitHub](https://docs.github.com/en/actions) and the [pipeline in GitLab](https://docs.gitlab.com/ee/ci/pipelines/).

## Examples

### Code

```latex
\begin{lstlisting}[style=Java, caption=Hello World]
public static void main(String[] args) {
	System.out.println("Hello World!");
}
\end{lstlisting}
```

### Figure

```latex
\begin{figure}[ht]
	\centering 
	\includegraphics{05_resources/image/name} 
    \caption{headline}
    \label{img:name}
\end{figure} 
```

### Table

```latex
\begin{table}[ht]
	\centering
	\begin{tabular}{c|c}
		Column 1 & Column 2 \\
		\hline
		1 & 2 \\
		3 & 4 \\
	\end{tabular}
	\caption{headline}
	\label{tab:name}
\end{table}
```

## Further Reading

* [Create a repository with template](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template)
* [Best Way to Start Using LaTex](https://tex.stackexchange.com/questions/4420/best-way-to-start-using-latex-tex)
* [LaTex Intro of the WHZ](https://bildungsportal.sachsen.de/opal/auth/RepositoryEntry/10599825411)
* [Organize your literature](https://www.jabref.org/)
* [Table Generator](https://www.tablesgenerator.com/)
