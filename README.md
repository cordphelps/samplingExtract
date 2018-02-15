



## precision farming sampling extract from 

[Spatial Data Analysis in Ecology and Agriculture using R](http://www.plantsciences.ucdavis.edu/plant/sda.htm)

---


##
read data with R:

```R
	> library(RCurl)
	> source.url <- c("https://raw.githubusercontent.com/cordphelps/samplingExtract/master/data/Set4.296wheatyield.csv")
	> dataframe.df <- read.csv(text=getURLContent(source.url), header=TRUE, row.names=1)
```
---


## License
[Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)

Data and Content distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.


## Content Author
 Richard Plant // [](http://www.plantsciences.ucdavis.edu/plant/index.htm)








 




