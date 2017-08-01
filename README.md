# Movie-Violence
*Final project for ECON 412*

### Background

In "Does Movie Violence Increase Violent Crime?", Dahl and DellaVigna find that "violent crime decreases on days with larger theater audiences for violent movies." They argue that this effect is the net effect of two opposing mechanisms at work in the relationship between violent movies and violent behavior. 

The first is the *incapacitation effect*, where violent movies disproportionately attract people who are statistically more likely to engage in violent behavior. When a popular violent movie arrives in theaters, these people spend their evenings at the movie theater, where it is very unlikely that they will engage in violent behavior, rather than at some other venue, such as a bar, where they would be more likely to engage in violent behavior. The second mechanism is the *arousal effect,* which is the popular idea that seeing violence induces audiences to engage in violent behaviors. While the incapacitation effect outweighs the arousal effect overall, Dahl and DellaVigna find evidence for both effects in their paper.

### Project

In this project, I attempt to more carefully study the effects of expected versus unexpected movie violence on violent behavior. I propose that it is only the *expectation* of seeing violence in a movie that drives the incapacitation effect of movies on violent crime. Expectations of violence in movies, however, do not necessarily match the actual violence shown in those movies.

I show that there is significant variation between actual movie violence (scraped from kids-in-mind.com ratings) and expected movie violence (computed from MPAA rating and movie genre). I run regression analyses to exploit this variation in order to find the effects of differences between actual and expected movie violence.

### Results

Unfortunately, in this project I am unable to identify a clear effect of movies that are significantly more or less violent than expected. This is likely due to many reasons. For one, my dataset is not as complete as Dahl and DellaVigna’s dataset. Also, my measure of “expected movie violence” is only a rough approximation of such expectations (also, the method by which it is computed minimizes the variation that my project aims to exploit in some sense). Nonetheless, I believe that the strategies that I suggest can, with more complete data, lead to useful insights into the differences between the incapacitation and arousal effects of violent movies.
