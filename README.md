# SampleSizeReport
[![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip) 

## Project concept 

This is a package that simplifies the approaches used to generate reports (tables, figures) for sample size estimations. 

- [ ] An S3/S4/R7 type object that can encapsulate what users might need to specify a sample size estimation problem.   
- [ ] This object can then be dispatched to functions corresponding to the requirements, mainly [`presize` package](https://ctu-bern.github.io/presize/),
    and `pwr`, and generate an output that is also a S3/S4/R7 object.  
- [ ] Plotting, Reporting, and Table methods can then be written to generate reports.  
- [ ] Instead of using Rshiny shells, use static reactable (see [forestly](https://elong0527.github.io/forestly/articles/forestly.html))   

## Additional considerations 

- Extending the `pwr` for more approaches.  
- Simulations (??). 
