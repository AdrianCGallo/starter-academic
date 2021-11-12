---
title: Key predictors of soil organic matter vulnerability to mineralization differ with depth at a continental scale


# Publication type.
# Legend: 
# 0 = Uncategorized; 
# 1 = Conference paper; 
# 2 = Journal article;
# 3 = Preprint / Working Paper; 
# 4 = Report; 
# 5 = Book; 
# 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Biogeochemistry
publication_short: Biogeochemistry
location: Biogeochemistry

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-11-06"
date_end: 
all_day: true



summary: SOM *storage* is not the same as its *vulnerability*. This was a 1-yr incubation experiment from NEON's A and B horizons ran by Tyler Weiglein at Virginia Tech as his Masters degree. We found that predictors of soil carbon vulnerability (based on CO2 respiration) were different for surface and subsurface horizons. Turns out, you need to dig deeper to find out the whole story on soils. 

abstract: "Soil organic matter (SOM) is the largest terrestrial pool of organic carbon, and potential carbon-climate feedbacks involving SOM decomposition could exacerbate anthropogenic climate change. However, our understanding of the controls on SOM mineralization is still incomplete, and as such, our ability to predict carbon-climate feedbacks is limited. To improve our understanding of controls on SOM decomposition, A and upper B horizon soil samples from 26 National Ecological Observatory Network (NEON) sites spanning the conterminous U.S. were incubated for 52 weeks under conditions representing site-specific mean summer temperature and sample- specific field capacity (-33 kPa) water potential. Cumulative carbon dioxide respired was periodically measured and normalized by soil organic C content to calculate cumulative specific respiration (CSR), a metric of SOM vulnerability to mineralization. The Boruta algorithm, a feature selection algorithm, was used to select important predictors of CSR from 159 variables. A diverse suite of predictors was selected (12 for A horizons, 7 for B horizons) with predictors falling into three categories corresponding to SOM chemistry, reactive Fe and Al phases, and site moisture availability. The relationship between SOM chemistry predictors and CSR was complex, while sites that had greater concentrations of reactive Fe and Al phases or were wetter had lower CSR. Only three predictors were selected for both horizon types, suggesting dominant controls on SOM decomposition differ by horizon. Our findings contribute to the emerging consensus that a broad array of controls regulates SOM decomposition at large scales and highlight the need to consider changing controls with depth.
"




authors: []
tags: [NEON, SOC, Continental, Vulnerability, Incubations, Boruta Algorithm]

# Is this a featured talk? (true/false)
featured: false

image: 
  focal_point: Smart


links:
- icon: google-scholar 
  icon_pack: ai
  name: Google Scholar
  url: https://scholar.google.com/scholar?hl=en&as_sdt=0%2C38&q=Key+predictors+of+soil+organic+matter+vulnerability+to+mineralization+differ+with+depth+at+a+continental+scale+TL+Weiglein&btnG=
url_code: ""
url_pdf: TalksPubs/Weiglein_2021_SOM_Predictors.pdf
url_slides: ""
url_video: ""


# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.

projects:
- NEON

---

#### TLDR   
We learned from our previous paper ([Nave 2021]({{< relref "/publication/21_Nave_SOC_Patterns" >}})) that SOM looks different across ecosystems. In this paper we move beyond simple storage calculations but onto SOM *vulnerability*. There is no universal way to define soil C vulnerability (chemical bond strength, carbon age, molecular size, etc..) but the transformation from SOM(s,l) to CO2(g) sure seems like good way to do it. 

Very few research run incubations for an entire year, few others run incubations with anything other than Organic or A-horizons, and almost nobody does year-long incubations with multiple horizons and multiple temperature + moisture conditions. This was a 1-yr incubation experiment from NEON's A and B horizons ran by Tyler Weiglein at Virginia Tech. This was a version of his Masters project, but with some changes. One change from his masters is that we used only the ambient temperature and field capacity soil incubations. There will be a subsequent paper that will look at comparisons between the moisture/temperature treatments. 

In this paper, we found that the vulnerability (based on CO2 respiration) of soil carbon in A horizons was different than B horizons. Even though we had ~160 predictor variables, the most consistent factor was the site's climate moisture deficit (a balance between incoming precipitation and the potential evaporation). There were also correlations with SOM chemistry and Fe/Al phases in A and B-horizons. Nonetheless, there could be much more said about this work (just the Boruta Algorithm is a fascinating statistical tool) but subsequent papers will really tease apart WHY these variables were so important, and whether we can predict what may happen under a warming world and/or changing precipitation patters. 

{{% staticref "TalksPubs/Weiglein_2021_SOM_Predictors.pdf" "newtab" %}}Download the PDF{{% /staticref %}}
