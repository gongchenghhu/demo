<div style="display: block; margin: 0 auto; width: 50%; background: #ccc;">
<div style="overflow-x: auto; overflow-y: auto; height: auto; width:1100px;">
<h1>Use intermediate speaker representation in multi-speaker TTS system to generate a new speakers’ voice</h1>
<p>Test sentence: "There is a way to measure the acute emotional intelligence that has never gone out of style."</p>
 </div>
<h2> LibriSpeech Result </h2>
<div style="overflow-x: auto; overflow-y: auto; height: 800px; width:1100px;">
<table border = "0.5">
 <tr>
  <td>
   reference speaker
  </td>
 </tr>
<tr>
<td>A<audio src="audioL/1.wav" controls width="10"></audio></td>
<td>B<audio src="audioL/2.wav" controls></audio></td>
<td>C<audio src="audioL/3.wav" controls></audio></td>
<td>D<audio src="m20/1.wav" controls></audio></td>
</tr>
<tr>
<td>single speaker enbedding</td>
</tr>
 <tr>
<td>WaveRNN</td>
</tr>
<tr>
<td>A<audio src="audioL/4.wav" controls width="10"></audio></td>
<td>B<audio src="audioL/5.wav" controls></audio></td>
<td>C<audio src="audioL/6.wav" controls></audio></td>
<td>D<audio src="l20/2.wav" controls></audio></td>
</tr>
 <tr>
<td>G&L</td>
</tr>
<tr>
<td>A<audio src="audioL/7.wav" controls width="10"></audio></td>
<td>B<audio src="audioL/8.wav" controls></audio></td>
<td>C<audio src="audioL/9.wav" controls></audio></td>
<td>D<audio src="l20/3.wav" controls></audio></td>
</tr>
 <tr>
 <td>two speakers embedding</td>
</tr>
 <tr>
<td>WaveRNN</td>
</tr>
<tr>
<td>0.5A+0.5B<audio src="audioL/10.wav" controls width="10"></audio></td>
<td>0.5B+0.5C<audio src="audioL/11.wav" controls></audio></td>
<td>0.5A+0.5C<audio src="audioL/12.wav" controls></audio></td>
 <td>0.5A+0.5D<audio src="l20/4.wav" controls></audio></td>
</tr>
 <tr>
<td>G&L</td>
</tr>
<tr>
<td>0.5A+0.5B<audio src="audioL/13.wav" controls width="10"></audio></td>
<td>0.5B+0.5C<audio src="audioL/14.wav" controls></audio></td>
<td>0.5A+0.5C<audio src="audioL/15.wav" controls></audio></td>
 <td>0.5A+0.5D<audio src="l20/5.wav" controls></audio></td>
</tr>
<tr>
 <td>
  three speakers enbedding
  </td>
</tr>
 <tr>
 <td>
  WaveRNN
  </td>
</tr>
<td>0.33A+0.33B+0.33C<audio src="audioL/16.wav" controls width="10"></audio></td>
 <td>0.33A+0.33C+0.33D<audio src="l20/6.wav" controls width="10"></audio></td>
</tr>
<tr>
 <td>
  G&L
  </td>
</tr>
<td>0.33A+0.33B+0.33C<audio src="audioL/17.wav" controls width="10"></audio></td>
<td>0.33A+0.33C+0.33D<audio src="l20/7.wav" controls width="10"></audio></td>
</tr>
</table>
</div>
<div style="overflow-x: auto; overflow-y: auto; height: 800px; width:1100px;">
<h2> M-AILABS Result </h2>
<table border = "0">
 <tr>
  <td>
   reference speaker
  </td>
 </tr>
<tr>
<td>A<audio src="audioL/1.wav" controls width="10"></audio></td>
<td>B<audio src="audioL/2.wav" controls></audio></td>
<td>C<audio src="audioL/3.wav" controls></audio></td>
 <td>D<audio src="m20/1.wav" controls></audio></td>
</tr>
<tr>
<td>single speaker embedding</td>
</tr>
 <tr>
<td>WaveRNN</td>
</tr>
<tr>
<td>A<audio src="audioM/4.wav" controls width="10"></audio></td>
<td>B<audio src="audioM/5.wav" controls></audio></td>
<td>C<audio src="audioM/6.wav" controls></audio></td>
 <td>D<audio src="m20/2.wav" controls></audio></td>
</tr>
 <tr>
<td>G&L</td>
</tr>
<tr>
<td>A<audio src="audioM/7.wav" controls width="10"></audio></td>
<td>B<audio src="audioM/8.wav" controls></audio></td>
<td>C<audio src="audioM/9.wav" controls></audio></td>
 <td>D<audio src="m20/3.wav" controls></audio></td>
</tr>
 <tr>
 <td>two speakers enbedding</td>
</tr>
 <tr>
<td>WaveRNN</td>
</tr>
<tr>
<td>0.5A+0.5B<audio src="audioM/10.wav" controls width="10"></audio></td>
<td>0.5B+0.5C<audio src="audioM/11.wav" controls></audio></td>
<td>0.5A+0.5C<audio src="audioM/12.wav" controls></audio></td>
 <td>0.5A+0.5D<audio src="m20/4.wav" controls></audio></td>
</tr>
 <tr>
<td>G&L</td>
</tr>
<tr>
<td>0.5A+0.5B<audio src="audioM/13.wav" controls width="10"></audio></td>
<td>0.5B+0.5C<audio src="audioM/14.wav" controls></audio></td>
<td>0.5A+0.5C<audio src="audioM/15.wav" controls></audio></td>
 <td>0.5A+0.5D<audio src="m20/5.wav" controls></audio></td>
</tr>
<tr>
 <td>
  three speakers enbedding
  </td>
</tr>
 <tr>
 <td>
  WaveRNN
  </td>
</tr>
<td>0.33A+0.33B+0.33C<audio src="audioM/16.wav" controls width="10"></audio></td>
 <td>0.33A+0.33C+0.33D<audio src="m20/6.wav" controls width="10"></audio></td>
</tr>
<tr>
 <td>
  G&L
  </td>
</tr>
<td>0.33A+0.33B+0.33C<audio src="audioM/17.wav" controls width="10"></audio></td>
 <td>0.33A+0.33C+0.33D<audio src="m20/7.wav" controls width="10"></audio></td>
</tr>
</table>
</div>
</div>
