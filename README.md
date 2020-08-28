# Iris-Dataset-Classfication-using-Naive-Bayes
Naive Bayes classification approach to identify the different species of Iris flowers. 
<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <mi>P</mi>
  <mo stretchy="false">(</mo>
  <msub>
    <mi>x</mi>
    <mi>i</mi>
  </msub>
  <mo>&#x2223;</mo>
  <mi>y</mi>
  <mo stretchy="false">)</mo>
  <mo>=</mo>
  <mfrac>
    <mn>1</mn>
    <msqrt>
      <mn>2</mn>
      <mi>&#x3C0;</mi>
      <msubsup>
        <mi>&#x3C3;</mi>
        <mi>y</mi>
        <mn>2</mn>
      </msubsup>
    </msqrt>
  </mfrac>
  <mi>exp</mi>
  <mo data-mjx-texclass="NONE">&#x2061;</mo>
  <mrow data-mjx-texclass="INNER">
    <mo data-mjx-texclass="OPEN">(</mo>
    <mo>&#x2212;</mo>
    <mfrac>
      <mrow>
        <mo stretchy="false">(</mo>
        <msub>
          <mi>x</mi>
          <mi>i</mi>
        </msub>
        <mo>&#x2212;</mo>
        <msub>
          <mi>&#x3BC;</mi>
          <mi>y</mi>
        </msub>
        <msup>
          <mo stretchy="false">)</mo>
          <mn>2</mn>
        </msup>
      </mrow>
      <mrow>
        <mn>2</mn>
        <msubsup>
          <mi>&#x3C3;</mi>
          <mi>y</mi>
          <mn>2</mn>
        </msubsup>
      </mrow>
    </mfrac>
    <mo data-mjx-texclass="CLOSE">)</mo>
  </mrow>
</math>

P(x_i \mid y) = \frac{1}{\sqrt{2\pi\sigma^2_y}} \exp\left(-\frac{(x_i - \mu_y)^2}{2\sigma^2_y}\right)
