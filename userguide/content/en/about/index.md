---
title: About
linkTitle: About
menu: {main: {weight: 70}}

resources:
  - src: '**Conference202502*.jpeg'
    params:
      byline: '*Photo*: Conference'
params:
  message: Some _message_.
cSpell:ignore: imgproc pageinfo Bjørn Pedersen
---

{{% blocks/cover title="About" height="auto" %}}

On the morning of July 6, 2025, the Dali Tsung-Dao Lee Center for Sciences and Arts was officially inaugurated at the Pacific Care Home Dali International Holiday Retirement Community. 

Spearheaded by Academician Ding Hong, Deputy Director of Tsung-Dao Lee Institute at Shanghai Jiao Tong University, the center is jointly established by the Cang-Er Center for Scientific and Artistic Exchange of the Dali Bai Autonomous Prefecture and the Pacific Care Home Dali International Holiday Retirement Community. 

Inspired by Nobel Laureate Tsung-Dao Lee’s vision that “science and art are two sides of the same coin,” the center aspires to become a world-class interdisciplinary innovation platform—integrating science, art, and nature.
{{% /blocks/cover %}}

{{% blocks/section color="gray" height="auto"%}}

## Events
{{% imgproc Conference202502.jpeg Fit "400x300" %}}  
{{% /imgproc %}}

{{% imgproc spruce Fill "400x450" %}}
Norway Spruce *Picea abies* shoot with foliage buds.
{{% /imgproc %}}


{{< cardpane >}}
  {{< card header="**February 2025**" title="International Conference on Majorana Zero Modes: from Topological Superconductors to Non-Abelian Braiding Statistics" >}}
    Content card 1  
    {{% imgproc Conference202502.jpeg Fit "400x300" %}}  
    {{% /imgproc %}}
    *Majorana Conference Poster*
  {{< /card >}}

  {{< card header="**July 2025**" title="Symposium on the Beauty of Science and Art" >}}
    Content card 2  
    {{< imgproc "Symposium202507.jpg" Fit "400x300" >}}  
    *Symposium Poster*
  {{< /card >}}

  {{< card header="**Imagine**3" >}}
    Content card 3  
    {{< imgproc "imagine.jpg" Fit "400x300" >}}  
    *Artistic Imagination*
  {{< /card >}}
{{< /cardpane >}}


{{% /blocks/section %}}

{{ with resources.GetMatch "conference202502.jpeg" }}
  <img src="{{ .RelPermalink }}" alt="Conference Poster" width="400">
{{ end }}


{{% blocks/section color="300" %}}

### Residency Program

Residency Program
We offer residencies ranging from two weeks to three months, including:
* Private studios or lab spaces
* Accommodation and living support
* Opportunities for interdisciplinary exchange with other residents
* Platforms to present work to the public
[Learn more...](/docs/deployment/)
{{% /blocks/section %}}

{{% blocks/section color="light" %}}

### Governance

The Dali Center for Science & Art is creator-driven, with a lean administrative team that channels the majority of resources into academic and artistic activities.
Volunteers, board members, and partners contribute significant time and energy each year to ensure the Center remains open, free, and of the highest quality.
[Learn more...](/docs/deployment/)
{{% /blocks/section %}}

{{% blocks/section color="white" %}}

### Visit Us

Whether you are a scientist, an artist, or simply curious about cross-disciplinary culture, you are welcome at the Dali Center for Science & Art. You can:
•   Attend public events  
•   Apply for the residency program  
•   Volunteer or become a partner  
•   Follow our online platforms for the latest updates  
[Learn more...](/docs/deployment/)
{{% /blocks/section %}}
