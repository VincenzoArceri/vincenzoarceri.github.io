---
layout: default
---

I am an Assistant Professor (non-tenure) in the Department of Mathematical, Physical, and Computer Sciences at the University of Parma, dealing with static analysis of Go language for blockchain applications, relational string analyses, and static analysis for dynamic languages.

## <a name="cv"></a>Short Bio
I have a Bachelor Degree in Computer Science (July 2014) and a Master Degree in Computer Science and Engineering – Computer Systems Security curriculum – (July 2016), both issued by the University of Verona. I was an UROP Student at the Imperial College London (Summer 2016), under the supervision of Prof. Sergio Maffeis. I joined the University of Verona in October 2016 as PhD student in Computer Science, under the supervision of Prof. Isabella Mastroeni and I got the PhD in May 2020, defending my PhD thesis titled “Taming Strings in Dynamic Languages – An Abstract Interpretation-based Static Analysis Approach”. From September 2019 to September 2021 I was a postdoctoral researcher at the Ca' Foscari University of Venice in the <a href="https://ssv.dais.unive.it/">Software and System Verification research group</a>. 
Currently, I am an Assistant Professor (non-tenure) in the Department of Mathematical, Physical, and Computer Sciences at the University of Parma, dealing with static analysis of Go language for blockchain applications, relational string analyses, and static analysis for dynamic languages.

My main research interests include static program analysis, string analysis and verification (in particular for dynamic languages), abstract interpretation and, more in general, formal methods for security programs.

## <a name="publications"></a>Projects

### LiSA
LiSA (Library for Static Analysis) eases the creation and implementation of static analyzers based on the Abstract Interpretation theory. LiSA provides an analysis engine that works on a generic and extensible control flow graph representation of the program to analyze. Abstract interpreters in LiSA are built for analyzing such representation, providing a unique analysis infrastructure for all the analyzers that will rely on it.

Building an analyzer upon LiSA boils down to writing a parser for the language that one aims to analyze, translating the source code or the compiled code towards the control flow graph representation of LiSA. Then, simple checks iterating over the results provided by the semantic analyses of LiSA can be easily defined to translate semantic information into warnings that can be of value for the final user.

LiSA is maintained by the <a href="https://ssv.dais.unive.it/">Software and System Verification group</a> @ Ca’ Foscari University of Venice, Italy, and it is distributed under the MIT license, and it is available on <a href="https://github.com/UniVE-SSV/lisa">GitHub</a>.


## <a name="publications"></a>Publications
### 2022
<table>
<tr>
   <td valign="top"><b>[c8]</b></td>
    <td>V. Arceri, M.Olliaro, A. Cortesi, P. Ferrara <i>Relational String Abstract Domains</i>, In Proceedings of the 23th International Conference on Verification, Model Checking, and Abstract Interpretation, VMCAI 2022, Philadelphia, January 16-19, 2022. <a href="https://link.springer.com/chapter/10.1007/978-3-030-94583-1_2">[link]</a> </td>
  </tr>
</table>
### 2021
<table>
       <tr>
   <td valign="top"><b>[j4]</b></td>
    <td>V. Arceri, M. Olliaro, A. Cortesi, I. Mastroeni <i>Completeness of String Analysis for Dynamic Languages
</i>, in Information and Computation, 104791, 2021 <a href="https://www.sciencedirect.com/science/article/pii/S0890540121001073#se0120">[link]</a></td>
  </tr>
		 <tr>
   <td valign="top"><b>[c7]</b></td>
    <td>P. Ferrara, L. Negrini, V. Arceri, A. Cortesi <i>Static Analysis for Dummies: Experiencing LiSA
</i>, in Proceedings of 10th ACM SIGPLAN International Workshop on the State of the Art in Program Analysis, SOAP 2021, June 22th, 2021 <a href="https://dl.acm.org/doi/10.1145/3460946.3464316">[link]</a></td>
  </tr>
	 <tr>
   <td valign="top"><b>[c6]</b></td>
    <td>I. Mastroeni, V. Arceri <i>Improving dynamic code analysis by code abstraction
</i>, in Proceedings of 9th International Workshop on Verification and Program Transformation, VPT 2021, March 27th and 28th, 2021 <a href="http://eptcs.web.cse.unsw.edu.au/paper.cgi?VPT2021.2">[link]</a></td>
  </tr>
	 <tr>
   <td valign="top"><b>[j3]</b></td>
    <td>V. Arceri, I. Mastroeni <i>Analyzing Dynamic Code: A Sound Abstract Interpreter for evil eval</i>, in ACM Transactions on Privacy and Security, 2021, Vol. 24, No. 2. <a href="https://dl.acm.org/doi/10.1145/3426470">[link]</a></td>
  </tr>
<tr>
   <td valign="top"><b>[c5]</b></td>
    <td>L.Negrini, V. Arceri, P. Ferrara, A. Cortesi <i>Twinning Automata and Regular Expressions for String Static Analysis</i>, in Proceedings of the 22nd International Conference on Verification, Model Checking, and Abstract Interpretation, VMCAI 2021, Online, January 17-22, 2021. <a href="https://link.springer.com/chapter/10.1007/978-3-030-67067-2_13">[link]</a> </td>
  </tr>
</table>

### 2020

<table>
	<tr>
    <td valign="top"><b>[j2]</b></td>
    <td>V. Arceri, I. Mastroeni, S. Xu <i>Static Analysis for ECMAScript String Manipulation Programs</i>, in Applied Science, SI: Static Analysis Techniques: Recent Advances and New Horizons, 2020 <a href="https://www.mdpi.com/2076-3417/10/10/3525">[link]</a></td>
  </tr>
 	<tr>
    <td valign="top"><b>[c4]</b></td>
    <td>V. Arceri, I. Mastroeni <i>A Sound Abstract Interpreter for Dynamic Code</i>, in Proceedings of the 35th ACM/SIGAPP Symposium On Applied Computing, SAC 2020, Brno, Czech Republic March 30 - April 3, 2020 <a href="https://dl.acm.org/doi/abs/10.1145/3341105.3373964">[link]</a></td>
  </tr>
</table>

### 2019

<table>
 	<tr>
    <td valign="top"><b>[c3]</b></td>
    <td>V. Arceri, M. Pasqua, I. Mastroeni <i>An Abstract Domain for Objects in Dynamic Programming languages</i>, in informal Proceedings of the 8th International Workshop on Numerical and Symbolic Abstract Domains, NSAD 2019, Porto, Portugal, October 8, 2019 <a href="https://link.springer.com/chapter/10.1007%2F978-3-030-54997-8_9">[link]</a></td>
  </tr>

  <tr>
    <td valign="top"><b>[c2]</b></td>
    <td>V. Arceri, M. Olliaro, A. Cortesi, I. Mastroeni <i>Completeness of Abstract Domains for String Analysis of JavaScript Programs</i>, in Proceedings of 16th International Colloquium of Theoretical Aspects of Computing, ICTAC 2019, Hammamet, Tunisia, October 31 - November 4, 2019 <a href="https://link.springer.com/chapter/10.1007%2F978-3-030-32505-3_15">[link]</a></td>
  </tr>

  <tr>
    <td valign="top"><b>[c1]</b></td>
    <td>V. Arceri, I. Mastroeni , <i>Static Program Analysis for String Manipulation Languages</i>, in Proceedings of 7th International Workshop on Verification and Program Transformation, VPT@Programming 2019, Genova, Italy, April 2, 2019 <a href="http://eptcs.web.cse.unsw.edu.au/paper.cgi?VPT2019.5.pdf">[link]</a></td>
  </tr>
</table>

### 2017

<table>
  <tr>
    <td valign="top"><b>[j1]</b></td>
    <td>V. Arceri, S. Maffeis, <i>Abstract Domains for Type Juggling</i>, in Electr. Notes Theor. Comput. Sci., 331, pp. 41-55, 2017. <a href="https://www.sciencedirect.com/science/article/pii/S1571066117300051">[link]</a></td>
  </tr>
</table>

### Ph.D. Thesis

<table>
  <tr>
    <td>V. Arceri, <i>Taming Strings in Dynamic Languages – An Abstract Interpretation-based Static Analysis Approach</i>, Ph.D. Thesis, 2020. <a href="http://hdl.handle.net/11562/1016351">[link]</a></td>
  </tr>
</table>

## <a name="talks"></a>Talks

### 2022

<table>
  <tr>
    <td>January</td>
    <td>Relational String Abstract Domains, VMCAI 2022 (online)</td>
  </tr>
</table>

### 2021

<table>
	<tr>
    <td>June</td>
    <td>Static Analysis for Dummies: Experiencing LiSA, SOAP@PLDI 2021 (online)</td>
  </tr>
</table>

### 2020

<table>
	<tr>
    <td>May</td>
    <td>Taming Strings in Dynamic Languages – An Abstract Interpretation-based Static Analysis Approach, PhD Thesis defence (online)</td>
  </tr>
  <tr>
    <td>March</td>
    <td>A Sound Abstract Interpreter for Dynamic Code, SAC 2020, Brno, Czech Republic (online)</td>
  </tr>
</table>

### 2019

<table>
  <tr>
    <td>November</td>
    <td>Completeness of Abstract Domains for String Analysis of JavaScript Programs, ICTAC 2019, Hammamet, Tunisia</td>
  </tr>
  <tr>
    <td>April</td>
    <td>Static Program Analysis for String Manipulation Languages, VPT 2019, Genova, Italy</td>
  </tr>
</table>

### 2016

<table>
  <tr>
    <td>September</td>
    <td>Abstract Domains for Type Juggling, NSAD 2016, Edimburgh, Scotland</td>
  </tr>
</table>