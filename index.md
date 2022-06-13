<img align="center" src="resources/toucan.png" style="  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 60%;" />


## Official Code

[https://github.com/DigitalPhonetics/IMS-Toucan](https://github.com/DigitalPhonetics/IMS-Toucan)

## Interactive Demo

[Hosted on Huggingface🤗 Spaces](https://huggingface.co/spaces/Flux9665/PoeticTTS)

## What's this?

We showcase a few samples of German poetry with different pronunciations. They differ in their realization of enjambments. The realizations of the enjambments can be edited in a fine-grained way using our human-in-the-loop text-to-speech. Being able to edit specific realizations of phenomena without affecting anything else is an invaluable tool for literary studies.

**What's an enjambment?** An enjambment occurs when the syntactic construction continues across the line break. [(click here to learn more)](https://en.wikipedia.org/wiki/Enjambment)

## Audio Samples

- <div style="display:inline;"> »Quellen hattest du ihm, hattest dem </div> <div style="color:darkgreen; display:inline; font-weight: bold;" > Flüchtigen <br> Kühle Schatten</div><div style="display:inline;"> geschenkt« <br>  <br> </div>

    <table style='width: 100%;'>
        <tr>
            <td bgcolor="#e4ffe3">Human Reference A with unemphasized enjambment</td>
            <td bgcolor="#e4ffe3"><audio controls="" ><source src="resources/Quellen_Zischler.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e4ffe3">Human Reference B with emphasized enjambment</td>
            <td bgcolor="#e4ffe3"><audio controls="" ><source src="resources/Quellen_Mönckeberg.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e5e3ff">Synthesized Reference A with unemphasized enjambment</td>
            <td bgcolor="#e5e3ff"><audio controls="" ><source src="resources/s2_p1_ref2.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e5e3ff">Synthesized Reference B with emphasized enjambment</td>
            <td bgcolor="#e5e3ff"><audio controls="" ><source src="resources/s2_p1_ref1.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e5e3ff">Realization A edited to have B's emphasized enjambment</td>
            <td bgcolor="#e5e3ff"><audio controls="" ><source src="resources/s2_p1_base2_pros_1.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e5e3ff">Realization B edited to have A's unemphasized enjambent</td>
            <td bgcolor="#e5e3ff"><audio controls="" ><source src="resources/s2_p1_base1_pros_2.wav" type="audio/wav"></audio></td></tr><tr>
        </tr>
    </table>

- <div style="display:inline;"> »Und die Gestade</div> <div style="color:darkgreen; display:inline; font-weight: bold;" > sahen <br> All</div><div style="display:inline;"> ihm nach« <br>  <br> </div>

    <table style='width: 100%;'>
        <tr>
            <td bgcolor="#e4ffe3">Human Reference A with unemphasized enjambment</td>
            <td bgcolor="#e4ffe3"><audio controls="" ><source src="resources/Gestade_Zischler.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e4ffe3">Human Reference B with emphasized enjambment</td>
            <td bgcolor="#e4ffe3"><audio controls="" ><source src="resources/Gestade_Mönckeberg.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e5e3ff">Synthesized Reference A with unemphasized enjambment</td>
            <td bgcolor="#e5e3ff"><audio controls="" ><source src="resources/s2_p2_ref2.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e5e3ff">Synthesized Reference B with emphasized enjambment</td>
            <td bgcolor="#e5e3ff"><audio controls="" ><source src="resources/s2_p2_ref1.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e5e3ff">Realization A edited to have B's emphasized enjambment</td>
            <td bgcolor="#e5e3ff"><audio controls="" ><source src="resources/s2_p2_base2_pros_1.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e5e3ff">Realization B edited to have A's unemphasized enjambent</td>
            <td bgcolor="#e5e3ff"><audio controls="" ><source src="resources/s2_p2_base1_pros_2.wav" type="audio/wav"></audio></td></tr><tr>
        </tr>
    </table>

- <div style="display:inline;"> »Lass endlich Vater! offenen Aug's mich </div> <div style="color:darkgreen; display:inline; font-weight: bold;" > dir <br> Begegnen</div><div style="display:inline;">!« <br>  <br> </div>

    <table style='width: 100%;'>
        <tr>
            <td bgcolor="#e4ffe3">Human Reference A with unemphasized enjambment</td>
            <td bgcolor="#e4ffe3"><audio controls="" ><source src="resources/Vater_Quadflieg.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e4ffe3">Human Reference B with emphasized enjambment</td>
            <td bgcolor="#e4ffe3"><audio controls="" ><source src="resources/Vater_Mönckeberg.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e5e3ff">Synthesized Reference A with unemphasized enjambment</td>
            <td bgcolor="#e5e3ff"><audio controls="" ><source src="resources/s5_p1_ref2.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e5e3ff">Synthesized Reference B with emphasized enjambment</td>
            <td bgcolor="#e5e3ff"><audio controls="" ><source src="resources/s5_p1_ref1.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e5e3ff">Realization A edited to have B's emphasized enjambment</td>
            <td bgcolor="#e5e3ff"><audio controls="" ><source src="resources/s5_p1_base2_pros_1.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e5e3ff">Realization B edited to have A's unemphasized enjambent</td>
            <td bgcolor="#e5e3ff"><audio controls="" ><source src="resources/s5_p1_base1_pros_2.wav" type="audio/wav"></audio></td></tr><tr>
        </tr>
    </table>

- <div style="display:inline;"> »Hast denn du nicht zuerst den</div> <div style="color:darkgreen; display:inline; font-weight: bold;" > Geist <br> Mit deinem Strahl</div><div style="display:inline;"> aus mir geweckt?« <br>  <br> </div>

    <table style='width: 100%;'>
        <tr>
            <td bgcolor="#e4ffe3">Human Reference A with unemphasized enjambment</td>
            <td bgcolor="#e4ffe3"><audio controls="" ><source src="resources/Hast_Quadflieg.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e4ffe3">Human Reference B with emphasized enjambment</td>
            <td bgcolor="#e4ffe3"><audio controls="" ><source src="resources/Hast_Mönckeberg.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e5e3ff">Synthesized Reference A with unemphasized enjambment</td>
            <td bgcolor="#e5e3ff"><audio controls="" ><source src="resources/s5_p2_ref2.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e5e3ff">Synthesized Reference B with emphasized enjambment</td>
            <td bgcolor="#e5e3ff"><audio controls="" ><source src="resources/s5_p2_ref1.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e5e3ff">Realization A edited to have B's emphasized enjambment</td>
            <td bgcolor="#e5e3ff"><audio controls="" ><source src="resources/s5_p2_base2_pros_1.wav" type="audio/wav"></audio></td></tr><tr>
            <td bgcolor="#e5e3ff">Realization B edited to have A's unemphasized enjambent</td>
            <td bgcolor="#e5e3ff"><audio controls="" ><source src="resources/s5_p2_base1_pros_2.wav" type="audio/wav"></audio></td></tr><tr>
        </tr>
    </table>
    
    
<br><br><br>
<div bgcolor="#e5e3ff"> All samples shown with this background are synthetic.</div> The voice used for generating the samples is based on Hanns Zischler's recordings which come with the following copyright notice:

*Florian Michel (Ton) und Hanns Zischler (Sprecher) im Auftrag des Deutschen Literaturarchivs Marbach (2020)*
