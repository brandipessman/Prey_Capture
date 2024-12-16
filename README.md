# Rapid changes in vibratory noise elicit flexible responses from urban, but not rural, web-building spiders

The following data and code are provided as a reference for the associated future publication. This publication was written in association with my Ph.D. dissertation.

## Who:

> > 👩 Authors: **Brandi Pessman**, Abdallah Abdallah, and Eileen Hebets

> > 🕷️ S️tudy Organism: *Agelenopsis pennsylvanica* (the funnel-weaving spider or grass spider)

## What:

> > Environmental noise can mask or degrade information crucial for animal behavioral responses, with anthropogenic noise in urban habitats posing a particularly intense, pervasive, and novel threat. In response, animals may exhibit behaviors that alter the transmission of information, potentially incurring costs such as energy loss, increased predation risk, or loss of critical information. While some animals may cope by modifying and reverting behaviors instantaneously as noise levels fluctuate, the extent to which less immediately flexible behavioral plasticity constrains responses in variable noise environments remains unclear. Here, we focus on the funnel-weaving spider, Agelenopsis pennsylvanica, which demonstrates plasticity in vibration transmission across their semi-permanent webs in response to different vibratory noise levels. We investigated the flexibility of prey capture and mating behavior in unvarying and variable vibratory noise environments. We collected spiders from rural and urban habitats, characterized by spatiotemporal variation in vibratory noise, and simulated quiet or loud vibratory noise environments during web construction in the laboratory. Spiders in unvaryingly loud environments attacked prey stimuli faster, irrespective of origin, potentially at the cost of accurate prey assessment. Rural spiders demonstrated limited flexibility to rapid shifts in noise environments – slowing attack rates when the current noise environment mismatched the web construction conditions and delaying an essential mating phase on webs built in unfamiliar loud conditions. Conversely, urban spiders exhibited greater flexibility, indicating that previous experience may be beneficial for coping with loud, variable environments. We suspect that there is an interplay in behavioral plasticity in modulating web-borne vibration transmission during web construction and dealing with sudden uncertainty in shifting environments. Our findings underscore the importance of lifelong exposure to anthropogenic noise in shaping flexible responses to loud, variable environments. 
The code presented in this repository walks through the analysis of this data, including:

-   Wrangling/munging the data files ([1_data_wrangling.Rmd](./1_data_wrangling.Rmd))

-   Analyses of attack rates of rural/urban spiders under quiet/loud vibratory treatments ([2_prey_capture.Rmd](./2_prey_capture.Rmd))

-   Analyses of male/female mating behaviors under quiet/loud vibratory treatments ([3_mating.Rmd](./3_mating.Rmd))

-   Analyses of learning experiment conducted by Southeast Community College Animal Behavior Course led by me ([4_learning_scc.Rmd](./4_learning_scc.Rmd))

## When:

> > 📓 Date Collected: Spiders collected June 23-July 22, 2021, August 4-10, 2022; prey capture data collected September4-September 26, 2021

## Where:

> > 📓 Data collected in: Lincoln, Nebraska


## Why:

> > While behavioral modifications enabling information detection above background noise may be advantageous by reducing instances of prey detection failure or missed mating opportunities, the inability to assess prey and mates may come with costs if spiders cannot discern prey quality, distinguish prey from predators, or evaluate mate quality or receptivity. Previous experience – whether genetic adaptation, juvenile experience, or maternal effects – seems to be at play as urban spiders exhibited greater behavioral flexibility than rural spiders, likely due to urban spiders being more familiar with loud and rapidly changing noise environments. These findings highlight the complex interplay between release from anthropogenic noise masking effects and the potential functional implications of the resulting behavioral plasticity, a trade-off with potentially long-term implications for predator-prey interactions and sexual signals. They also underscore the urgent need for further research on the effects of anthropogenic noise on arthropods and in the vibratory sensory channel, both understudied players in urban habitats.

## How:

> > 💻 R programming language

Analyses include:

-   Negative binomial generalized linear models ([2_prey_capture.Rmd](./2_prey_capture.Rmd), [3_mating.Rmd](./3_mating.Rmd))
-   Zero-Inflated negative binomial generalized linear models ([3_mating.Rmd](./3_mating.Rmd))
-   Robust linear models ([3_mating.Rmd](./3_mating.Rmd))
-   Binomial generalized linear models ([3_mating.Rmd](./3_mating.Rmd))
-   Kaplan-Meier Survival Curves ([4_learning_scc.Rmd](./4_learning_scc.Rmd))


> > 🎶️ Raven Pro Software for the analysis of vibrations
