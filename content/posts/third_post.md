---
title: "Experimente mit Arduino"
date: 2022-12-06T17:37:41+01:00
draft: false
--- 

## 16. November 2022

 In diesem Blogpost ist in drei Teile unterteilt, für jeden Tag ein Teil. Im ersten davon geht es um den 16. November 2022 an dem wir uns an die ersten kleineren Experimente mit dem Arduino, verschiedenen Sensoren und sonstigem Zubehör herangewagt haben. Mein erster Versuch war es, eine LED zum leuchten zu bringen und mit dem Arduino anzusteuern. Das stellte sich als leichter heraus wie gedacht, da die Funktionsweise relativ selbsterklärend war. Danach wollte ich einen Button verwenden der de LED zum leuchten bringt wenn er gedrückt wird. 

{{<figure src="../img/single_btn.jpg"  width="60%"  height="60%">}}

{{<figure src="/img/single_btn.jpg"  width="60%"  height="60%">}}

![single button](/single_btn.jpg)

![single button](/static/single_btn.jpg)

![single button](../../static/single_btn.jpg)

<img src="/single_btn.jpg" />

<img src="/static/single_btn.jpg" />

<img src="../../static/single_btn.jpg" />


 Da auch das ohne größere Probleme funktioniert hat, wollte ich ein neues Bauteil ausprobieren. Mithilfe eines kleinen Speakers und einer Matrix aus Buttons versuchte ich eine Art "Klavier" zu bauen das je nach dem welcher der 16 Buttons gedrückt wurde, einen verschieden hohen Ton von sich gibt. Die Verkabelung ging mithilfe einer Anleitung recht intuitiv, allerdings war das Problem dann softwareseitig. Zunächst musste ich die Buttons in einem Array speichern und ihnen anschließend die richtigen Töne zuweisen. 

## 