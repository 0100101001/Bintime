# Bintime

## Test task.
### Please, automate these 5 tasks using Java programming language.
#### 1. Select a random filter and check that the result set have have the same quantity of products as value of selected filter (the number of products in parentheses next to the filter being selected).
1. Open the page https://www.centralpoint.nl/notebooks-laptops/
2. Choose a random value of a random filter. (except the “Prijs” filter and “Sortering”).
3. Click “Zoeken” button after checking filter value.
4. The number of products in the result set should be the same as the value of the selected filter
(the number of products in parentheses next to the filter being selected).
#### 2. Apply “Prijs” filter and check that result set doesn’t contain price less than minimum price that we set.
1. Open the page https://www.centralpoint.nl/monitoren/
2. Set minimum price for “Prijs” filter equal to 1000 euro and maximum price equal to 5000
euro.
#### 3. Click “Zoeken” button after setting.
4. Result set doesn’t have to contain cheaper product than 1000 euro.
3. REST test.
1. Do get request for http://restcountries.eu/rest/v1/
2. The request status should be equal to 200
3. Check that response type is JSON
4. Check that Latvia has border with Estonia
#### 4. REST test
1. Do get request for http://restcountries.eu/rest/v1/
2. The request status should be equal to 200
3. Check that response type is JSON
4. Check that Ukraine has area more than 500000.0
5. Output values: Name, Capital, Region, Population, Borders.
#### 5. There is a list of ProdId, please write one test-case that will search for each product on https://www.centralpoint.nl/ (filling search field and click search button) and check if product page for according product is opened after searching.

```javascript
ProdId list: {
    J153289
    MQ3D2ZD/A
    L36852-H2436-M101
    1WZ03EA#ABH
    875839-425
    C5J91A#B19
    FM32SD45B/10
    204446-101
    GV-N710D3-1GL
    02G-P4-6150-KR
}
```
