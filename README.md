# ESGF Melbourne (dev)

## Data

Minimum daily temperatures over 10 years (1981-1990) in the city Melbourne, Australia.

![Daily temperature evolution](docs/pics/temperature_evolution.png "Daily Temperature Evolution")

## Objective

We want to build a model able to predict the **daily** temperature in Melbourne over the **next year**.

## Evaluation

Fit one or more models using the data strictly anterior to the evaluation years 
`t=1987`, `t=1988` and `t=1989` in order to predict the daily temperature 
during the year `t=1987`, `t=1988` and `t=1989` respectively.

### Results

Choose a suitable metric to evaluate the performance of your models. 
Report the metric in the following table. 

For each evaluation year `t`, you must report the performance considering `k=3`, `k=6` and `k=12` months of data following `t`.

<table>
    <thead>
        <tr>
            <th>Evaluation year</th>
            <th>Next 3 months</th>
            <th>Next 6 months</th>
            <th>Next 12 months</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1987</td>
            <td>0.0267</td>
            <td>0.008257</td>
            <td>0.0277</td>
        </tr>
        <tr>
            <td>1988</td>
            <td>0.0402</td>
            <td>0.1512</td>
            <td>0.1645</td>
        </tr>
        <tr>
            <td>1989</td>
            <td>0.0277</td>
            <td>0.0189</td>
            <td>0.0198</td>
        </tr>
    </tbody>
</table>
