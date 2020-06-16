# forallx-pandocs

*there is an error in the ch5 and ch10 latex that is preventing conversion, that is why they are not present currently*

<table>
  <tr>
    <th>chapter</th><th>basic formatting</th><th>interactive</th>
  </tr>
  <tr>
    <td>ch1</td><td>yes</td><td>no</td>
  </tr>
  <tr>
    <td>ch2</td><td>no</td><td>no</td>
  </tr>
  <tr>
    <td>ch3</td><td>no</td><td>no</td>
  </tr>
  <tr>
    <td>ch4</td><td>no</td><td>no</td>
  </tr>
  <tr>
    <td>ch5</td><td>no</td><td>no</td>
  </tr>
  <tr>
    <td>ch6</td><td>no</td><td>no</td>
  </tr>
  <tr>
    <td>ch7</td><td>no</td><td>no</td>
  </tr>
  <tr>
    <td>ch8</td><td>no</td><td>no</td>
  </tr>
  <tr>
    <td>ch9</td><td>no</td><td>no</td>
  </tr>
  <tr>
    <td>ch10</td><td>no</td><td>no</td>
  </tr>
  <tr>
    <td>ch11</td><td>no</td><td>no</td>
  </tr>
  <tr>
    <td>ch12</td><td>no</td><td>no</td>
  </tr>
  <tr>
    <td>ch13</td><td>no</td><td>no</td>
  </tr>
</table>

## Rules

**indented blocks**: use html blockquote in the markdown

    <blockquote>
    line1 <br/>
    line2 <br/>
    line3
    </blockquote>

**numbered lists**: depending on desired result, can use... <br/>

ordered list (ol). Default behavior prevents last line from being 'therefore symbol', but that can probably be overridden:

    <ol>
    <li>line1</li>
    <li>line2</li>
    <li>line3</li>
    </ol>

blockquote with bolded numbers (works with therefore at end):

    <blockquote>
    **1.** line1 <br/>
    **2.** line2 <br/>
    [therefore] line3
    </blockquote>

there may also be a pandoc filter to do these. Update if this is found.

**...**