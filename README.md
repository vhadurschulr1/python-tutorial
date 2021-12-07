```python
!pip install requests
import requests
```

    Requirement already satisfied: requests in c:\python\lib\site-packages (2.25.1)
    Requirement already satisfied: urllib3<1.27,>=1.21.1 in c:\python\lib\site-packages (from requests) (1.26.4)
    Requirement already satisfied: certifi>=2017.4.17 in c:\python\lib\site-packages (from requests) (2020.12.5)
    Requirement already satisfied: chardet<5,>=3.0.2 in c:\python\lib\site-packages (from requests) (4.0.0)
    Requirement already satisfied: idna<3,>=2.5 in c:\python\lib\site-packages (from requests) (2.10)
    


```python
res = requests.get("https://covid2019-api.herokuapp.com/v2/current/US")
```


```python
res.json()
```




    {'data': [{'Province_State': 'California',
       'Confirmed': 5127121,
       'Deaths': 74911,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Texas',
       'Confirmed': 4356275,
       'Deaths': 74217,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Florida',
       'Confirmed': 3741058,
       'Deaths': 61789,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'New York',
       'Confirmed': 2788476,
       'Deaths': 57816,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Illinois',
       'Confirmed': 1854186,
       'Deaths': 29053,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Pennsylvania',
       'Confirmed': 1783118,
       'Deaths': 33962,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Ohio',
       'Confirmed': 1735925,
       'Deaths': 26851,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Georgia',
       'Confirmed': 1671787,
       'Deaths': 30691,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'North Carolina',
       'Confirmed': 1553112,
       'Deaths': 18860,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Michigan',
       'Confirmed': 1535147,
       'Deaths': 26239,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Tennessee',
       'Confirmed': 1327453,
       'Deaths': 17477,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Arizona',
       'Confirmed': 1295076,
       'Deaths': 22589,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'New Jersey',
       'Confirmed': 1275717,
       'Deaths': 28465,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Indiana',
       'Confirmed': 1130719,
       'Deaths': 17736,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Wisconsin',
       'Confirmed': 997688,
       'Deaths': 10134,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Virginia',
       'Confirmed': 983055,
       'Deaths': 14771,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Massachusetts',
       'Confirmed': 947463,
       'Deaths': 19516,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Minnesota',
       'Confirmed': 933025,
       'Deaths': 9778,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Missouri',
       'Confirmed': 929647,
       'Deaths': 15566,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'South Carolina',
       'Confirmed': 924958,
       'Deaths': 14314,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Alabama',
       'Confirmed': 848779,
       'Deaths': 16185,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Colorado',
       'Confirmed': 843851,
       'Deaths': 9380,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Kentucky',
       'Confirmed': 799695,
       'Deaths': 11289,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Washington',
       'Confirmed': 784129,
       'Deaths': 9436,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Louisiana',
       'Confirmed': 773621,
       'Deaths': 14837,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Oklahoma',
       'Confirmed': 674758,
       'Deaths': 12027,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Utah',
       'Confirmed': 605409,
       'Deaths': 3595,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Maryland',
       'Confirmed': 592679,
       'Deaths': 11255,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Iowa',
       'Confirmed': 534623,
       'Deaths': 7445,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Arkansas',
       'Confirmed': 533658,
       'Deaths': 8752,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Mississippi',
       'Confirmed': 516486,
       'Deaths': 10299,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Kansas',
       'Confirmed': 478613,
       'Deaths': 6747,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Nevada',
       'Confirmed': 461479,
       'Deaths': 8109,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Connecticut',
       'Confirmed': 430756,
       'Deaths': 8925,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Oregon',
       'Confirmed': 396501,
       'Deaths': 5268,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'New Mexico',
       'Confirmed': 324311,
       'Deaths': 5419,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Nebraska',
       'Confirmed': 316013,
       'Deaths': 3180,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Idaho',
       'Confirmed': 309314,
       'Deaths': 3977,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'West Virginia',
       'Confirmed': 301349,
       'Deaths': 4990,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Rhode Island',
       'Confirmed': 196949,
       'Deaths': 2948,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Montana',
       'Confirmed': 192590,
       'Deaths': 2768,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Puerto Rico',
       'Confirmed': 189325,
       'Deaths': 3273,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'South Dakota',
       'Confirmed': 168763,
       'Deaths': 2371,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'New Hampshire',
       'Confirmed': 167612,
       'Deaths': 1733,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'North Dakota',
       'Confirmed': 164811,
       'Deaths': 1954,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Delaware',
       'Confirmed': 156454,
       'Deaths': 2194,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Alaska',
       'Confirmed': 152537,
       'Deaths': 883,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Maine',
       'Confirmed': 123118,
       'Deaths': 1336,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Wyoming',
       'Confirmed': 112199,
       'Deaths': 1428,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Hawaii',
       'Confirmed': 88385,
       'Deaths': 1033,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'District of Columbia',
       'Confirmed': 67998,
       'Deaths': 1197,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Vermont',
       'Confirmed': 53131,
       'Deaths': 417,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Guam',
       'Confirmed': 19270,
       'Deaths': 267,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Virgin Islands',
       'Confirmed': 7549,
       'Deaths': 87,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Northern Mariana Islands',
       'Confirmed': 395,
       'Deaths': 3,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Grand Princess',
       'Confirmed': 103,
       'Deaths': 3,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'Diamond Princess',
       'Confirmed': 49,
       'Deaths': 0,
       'Recovered': 0,
       'Active': 0},
      {'Province_State': 'American Samoa',
       'Confirmed': 10,
       'Deaths': 0,
       'Recovered': 0,
       'Active': 0}],
     'dt': '12-07-2021',
     'ts': 1638835200}




```python
!pip install pandas
import pandas as pd
```

    Requirement already satisfied: pandas in c:\python\lib\site-packages (1.2.4)
    Requirement already satisfied: python-dateutil>=2.7.3 in c:\python\lib\site-packages (from pandas) (2.8.1)
    Requirement already satisfied: pytz>=2017.3 in c:\python\lib\site-packages (from pandas) (2021.1)
    Requirement already satisfied: numpy>=1.16.5 in c:\python\lib\site-packages (from pandas) (1.20.3)
    Requirement already satisfied: six>=1.5 in c:\python\lib\site-packages (from python-dateutil>=2.7.3->pandas) (1.16.0)
    


```python
df = pd.DataFrame(
    [(o['Province_State'], o['Deaths']) for o in res.json()['data']],
    columns=['Province_State','Deaths']
)
df.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Province_State</th>
      <th>Deaths</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>California</td>
      <td>74911</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Texas</td>
      <td>74217</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Florida</td>
      <td>61789</td>
    </tr>
    <tr>
      <th>3</th>
      <td>New York</td>
      <td>57816</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Illinois</td>
      <td>29053</td>
    </tr>
  </tbody>
</table>
</div>




```python
code = {'Alabama': 'AL',
        'Alaska': 'AK',
        'Arizona': 'AZ',
        'Arkansas': 'AR',
        'California': 'CA',
        'Colorado': 'CO',
        'Connecticut': 'CT',
        'Delaware': 'DE',
        'District of Columbia': 'DC',
        'Florida': 'FL',
        'Georgia': 'GA',
        'Hawaii': 'HI',
        'Idaho': 'ID',
        'Illinois': 'IL',
        'Indiana': 'IN',
        'Iowa': 'IA',
        'Kansas': 'KS',
        'Kentucky': 'KY',
        'Louisiana': 'LA',
        'Maine': 'ME',
        'Maryland': 'MD',
        'Massachusetts': 'MA',
        'Michigan': 'MI',
        'Minnesota': 'MN',
        'Mississippi': 'MS',
        'Missouri': 'MO',
        'Montana': 'MT',
        'Nebraska': 'NE',
        'Nevada': 'NV',
        'New Hampshire': 'NH',
        'New Jersey': 'NJ',
        'New Mexico': 'NM',
        'New York': 'NY',
        'North Carolina': 'NC',
        'North Dakota': 'ND',
        'Ohio': 'OH',
        'Oklahoma': 'OK',
        'Oregon': 'OR',
        'Pennsylvania': 'PA',
        'Rhode Island': 'RI',
        'South Carolina': 'SC',
        'South Dakota': 'SD',
        'Tennessee': 'TN',
        'Texas': 'TX',
        'Utah': 'UT',
        'Vermont': 'VT',
        'Virginia': 'VA',
        'Washington': 'WA',
        'West Virginia': 'WV',
        'Wisconsin': 'WI',
        'Wyoming': 'WY'}
```


```python
df['State_Abb'] = df.Province_State.map(code)
df.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Province_State</th>
      <th>Deaths</th>
      <th>State_Abb</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>California</td>
      <td>74911</td>
      <td>CA</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Texas</td>
      <td>74217</td>
      <td>TX</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Florida</td>
      <td>61789</td>
      <td>FL</td>
    </tr>
    <tr>
      <th>3</th>
      <td>New York</td>
      <td>57816</td>
      <td>NY</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Illinois</td>
      <td>29053</td>
      <td>IL</td>
    </tr>
  </tbody>
</table>
</div>




```python
df = df[~df['State_Abb'].isnull()]
```


```python
!pip install plotly
import plotly.express as px
```

    Requirement already satisfied: plotly in c:\python\lib\site-packages (5.4.0)
    Requirement already satisfied: tenacity>=6.2.0 in c:\python\lib\site-packages (from plotly) (8.0.1)
    Requirement already satisfied: six in c:\python\lib\site-packages (from plotly) (1.16.0)
    


```python
fig = px.choropleth(df, locations='State_Abb', color='Deaths', hover_name='Province_State', locationmode='USA-states', scope='usa')
```


```python
fig.show() #does not show output if viewing in github
```
```python
fig.write_html("./covid-deaths-by-state.html")
fig.write_image("./covid-deaths-by-state.png")
```

## Interactive Map

[Click for interactive map](https://vhadurschulr1.github.io/python-tutorial/covid-deaths-by-state.html)

## Static Map

![](./covid-deaths-by-state.png)
