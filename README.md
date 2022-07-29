<div>
   <h1 id="title">digi-gt</h1>
   <p id="paragraph">Ground truth for the digitized historic collections of Universitätsbibliothek Mannheim.
The transcriptions were done with eScriptorium, a transcription platform developed as part of the Scripta and RESILIENCE projects (https://gitlab.com/scripta/escriptorium/).</p>
   <h2>Metadata</h2>
   <dl class="grid">
      <dt id="Language">Language:</dt>
      <dd>deu, lat</dd>
      <dt id="Format">Format:</dt>
      <dd>Page-XML</dd>
      <dt id="Time">Time:</dt>
      <dd>1507-1555</dd>
      <dt id="GTT">GT Type:</dt>
      <dd>data_line</dd>
      <dt id="License">License:</dt>
      <dd>CC0 1.0</dd>
      <dt id="Project">Project:</dt>
      <dd>Die digitalen Sammlungen der Universitätsbibliothek Mannheim</dd>
      <dt id="Project-URL">Project-URL:</dt>
      <dd>https://digi.bib.uni-mannheim.de/</dd>
   </dl>
   <h2>Sources</h2>
   <h3>The volume of transcriptions:</h3>
   <table id="table_id">
      <thead>
         <tr>
            <th>TextLine</th>
            <th>Page</th>
            <th>TxtRegion</th>
         </tr>
      </thead>
      <tbody>
         <tr>
            <td>3011</td>
            <td>106</td>
            <td>379</td>
         </tr>
      </tbody>
   </table>
   <div id="transcriptions">
      <h3>List of transcriptions</h3>
      <div>
         <table class="noStyle"/>
         <table id="table_id" class="display">
            <thead>
               <tr>
                  <th>document</th>
                  <th>TxtRegion</th>
                  <th>TextLine</th>
                  <th>Page</th>
               </tr>
            </thead>
            <tbody>
               <tr>
                  <td>PPN477396054</td>
                  <td>43</td>
                  <td>291</td>
                  <td>11</td>
               </tr>
               <tr>
                  <td>PPN477396569</td>
                  <td>9</td>
                  <td>275</td>
                  <td>8</td>
               </tr>
               <tr>
                  <td>PPN1807527700</td>
                  <td>32</td>
                  <td>559</td>
                  <td>12</td>
               </tr>
               <tr>
                  <td>PPN506281272</td>
                  <td>72</td>
                  <td>273</td>
                  <td>13</td>
               </tr>
               <tr>
                  <td>PPN477366015</td>
                  <td>59</td>
                  <td>617</td>
                  <td>24</td>
               </tr>
               <tr>
                  <td>PPN1807526488</td>
                  <td>103</td>
                  <td>392</td>
                  <td>18</td>
               </tr>
               <tr>
                  <td>PPN477380670</td>
                  <td>61</td>
                  <td>604</td>
                  <td>20</td>
               </tr>
            </tbody>
         </table>
      </div>
   </div>
   <div id="extent">
      <h2>Extent</h2>
      <p>
        After exporting the transcriptions as PAGE XML files, those files were processed to remove empty lines:</p>
         
        perl -i -ne "tr|\r||d; next if /^\s*$/;print" *.xml
                            
   </div>
</div>
