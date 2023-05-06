Download Link: https://assignmentchef.com/product/solved-eecs340-assignment-2-asymptotic-notation
<br>
For the following statements, consider the functions <em>f</em>(<em>n</em>), <em>g</em>(<em>n</em>) and constant <em>c </em>such that <em>f</em>(<em>n</em>) ≥ 0, <em>g</em>(<em>n</em>) ≥ 0, and <em>c &gt; </em>0. Indicate whether the statements are true or false. If true prove the statement by providing a formal argument based on the definition of asymptotic notation, otherwise, provide a counter-example to prove that they are false.

(<em>a</em>) max{<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>)} = Θ(<em>f</em>(<em>n</em>) + <em>g</em>(<em>n</em>)).

(<em>b</em><sub>1</sub>) <em>f</em>(<em>n</em>) + <em>c </em>= <em>O</em>(<em>f</em>(<em>n</em>)).

(<em>b</em><sub>2</sub>) If <em>f</em>(<em>n</em>) ≥ 1, then <em>f</em>(<em>n</em>) + <em>c </em>= <em>O</em>(<em>f</em>(<em>n</em>)).

(<em>c</em><sub>1</sub>) If <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)), log(<em>f</em>(<em>n</em>)) ≥ 0 and log(<em>g</em>(<em>n</em>)) ≥ 0, then log(<em>f</em>(<em>n</em>)) = <em>O</em>(log(<em>g</em>(<em>n</em>))).

(<em>c</em><sub>2</sub>) If <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)), log(<em>f</em>(<em>n</em>)) ≥ 0 and log(<em>g</em>(<em>n</em>)) ≥ 1, then log(<em>f</em>(<em>n</em>)) = <em>O</em>(log(<em>g</em>(<em>n</em>))).

(<em>d</em><sub>1</sub>) <em>f</em>(2<em>n</em>) = Θ(<em>f</em>(<em>n</em>)).

(<em>d</em><sub>2</sub>) If <em>f</em>(<em>n</em>) = <em>O</em>(<em>n<sup>c</sup></em>), then <em>f</em>(2<em>n</em>) = <em>O</em>(<em>n<sup>c</sup></em>).

(<em>d</em><sub>3</sub>) If <em>f</em>(<em>n</em>) = Θ(<em>n<sup>c</sup></em>), then <em>f</em>(2<em>n</em>) = Θ(<em>f</em>(<em>n</em>)).

<h1>Problem 2</h1>

Assume , a and b are constants such that 0 . Sort the following functions in asymptotically increasing order and indicate when two or more functions are asymptotically equivalent (see definition below). Briefly justify your answers (no formal proof is needed).

<table width="436">

 <tbody>

  <tr>

   <td width="107"><em>n</em></td>

   <td width="136"><em>n</em></td>

   <td width="143"><em>a</em><em>n</em></td>

   <td width="50"><em>b</em><em>n</em></td>

  </tr>

  <tr>

   <td width="107"><em>a</em>log<em><sub>a</sub>n</em></td>

   <td width="136">log(<em>n<sup>a</sup></em>)</td>

   <td width="143">log(<em>n<sup>b</sup></em>)</td>

   <td width="50"><em>n/a</em></td>

  </tr>

  <tr>

   <td width="107"><em>n</em></td>

   <td width="136">(<em>n </em>+ <em>a</em>)<em><sup>b</sup></em></td>

   <td width="143"><em>n</em><em>a</em>+<em>b</em></td>

   <td width="50">(<em>n </em>+ <em>b</em>)<em><sup>a</sup></em></td>

  </tr>

 </tbody>

</table>

<em>                             n</em>−<em>a                                                          </em><em>n</em><em>a                                                                 </em>

(log<em>n</em>)<em><sup>a                                             </sup></em>log(<em>bn</em>)                                 <em>a<sup>n</sup></em>

<strong>Definition. </strong>Two functions <em>f</em>(<em>n</em>) and <em>g</em>(<em>n</em>) are <strong>asymptotically equivalent </strong>if and only if <em>f</em>(<em>n</em>) = Θ(<em>g</em>(<em>n</em>)).

<strong>Example. </strong>Suppose we are sorting the following functions: <em>n, </em>log(<em>n</em>)<em>, </em>2<em>n, </em>2<em><sup>n</sup>. </em>Then, the asymptotical ordering is: log(<em>.</em>