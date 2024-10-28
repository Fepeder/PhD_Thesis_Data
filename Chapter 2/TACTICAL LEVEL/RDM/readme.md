# Description
The tactical model is analyzed with a rolling horizon approach, with different reduced time horizons.
In the Decreasing Months Rolling approach (RDM) the reduced time horizon $S=12$ when $t=1$, $S=11$ for $t=2$, and so on in this way until $S=1$ when $t=12$.
For January the initial stock is the one actually realized = company data, and for the following months each initial stock is the one calculated by the model.
Model results for production shifts were used to calculate ending stock versus actual sales, in every first month of reduced horizons.
This final stock was valued against the final stock obtained by the company for comparison.
It also was used as the initial stock for the following month and the same procedure was followed for the following months as the analysis horizon gradually decreased.
The folders contain the instances used to solve the model both before and after the fine tuning process.


- [Before fine tuning](https://github.com/Fepeder/PhD_Thesis_Data/tree/main/Chapter%202/TACTICAL%20LEVEL/RDM/Before%20Fine%20Tuning)

- [After fine tuning](https://github.com/Fepeder/PhD_Thesis_Data/tree/main/Chapter%202/TACTICAL%20LEVEL/RDM/After%20Fine%20Tuning)
