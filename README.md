







```
r language BS21, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis portal gastropati TR, echo = (language == "TR")
## BS21 - portal gastropati {#sec-BS21 }
```


```
asis portal gastropathy EN, echo = (language == "EN")
## BS21 - portal gastropathy {#sec-BS21 }
```






```
r BS21 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS21-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS21/HE.html",
  file = "./screenshots/BS21-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/BS21/HE.html](https://images.patolojiatlasi.com/BS21/HE.html)





```
asis, echo = (language == "TR")

**portal gastropati**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS21-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS21/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS21/HE.html)
```

```
asis, echo = (language == "EN")

**portal gastropathy**

[![Click for Full Screen WSI](./screenshots/BS21-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS21/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS21/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS21/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS21/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

portal gastropati

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

portal gastropathy

:::

```









:::::








