---
layout: post
title: "Footsteps"
description: "A hobo unleashed..."
date: 2017-06-02
tags: [about neha]
comments: true
share: true
---

Footsteps as of June 2017.

__Africa__
* Ghana

__Asia__
* Hong Kong
* India
* Japan
* Malaysia
* Myanmar
* South Korea
* Thailand

__Europe__
* Belgium
* Czech Republic
* France
* Germany
* Italy 
* Netherlands
* Spain
* Switzerland
* United Kingdom

__North America__
* Canada
* United States

__South America__
* Argentina
* Brazil
* Chile
* Colombia
* Ecuador
* Peru

__Oceania__
Coming soon ;) 

__Antartica__
Coming soon ;)

<script src="https://www.amcharts.com/lib/3/ammap.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/maps/js/worldHigh.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/themes/dark.js" type="text/javascript"></script>
<div id="mapdiv" style="width: 1000px; height: 450px;"></div>
<div style="width: 1000px; font-size: 70%; padding: 5px 0; text-align: center; background-color: #535364; margin-top: 1px; color: #B4B4B7;"><a href="https://www.amcharts.com/visited_countries/" style="color: #B4B4B7;">Create your own visited countries map</a> or check out the <a href="https://www.amcharts.com/" style="color: #B4B4B7;">JavaScript Charts</a>.</div>
<script type="text/javascript">
var map = AmCharts.makeChart("mapdiv",{
type: "map",
theme: "dark",
projection: "mercator",
panEventsEnabled : true,
backgroundColor : "#535364",
backgroundAlpha : 1,
zoomControl: {
zoomControlEnabled : true
},
dataProvider : {
map : "worldHigh",
getAreasFromMap : true,
areas :
[
	{
		"id": "CA",
		"showAsSelected": true
	},
	{
		"id": "US",
		"showAsSelected": true
	},
	{
		"id": "AR",
		"showAsSelected": true
	},
	{
		"id": "BR",
		"showAsSelected": true
	},
	{
		"id": "CL",
		"showAsSelected": true
	},
	{
		"id": "CO",
		"showAsSelected": true
	},
	{
		"id": "EC",
		"showAsSelected": true
	},
	{
		"id": "PE",
		"showAsSelected": true
	},
	{
		"id": "GH",
		"showAsSelected": true
	},
	{
		"id": "HK",
		"showAsSelected": true
	},
	{
		"id": "IN",
		"showAsSelected": true
	},
	{
		"id": "JP",
		"showAsSelected": true
	},
	{
		"id": "MY",
		"showAsSelected": true
	},
	{
		"id": "MM",
		"showAsSelected": true
	},
	{
		"id": "KR",
		"showAsSelected": true
	},
	{
		"id": "TH",
		"showAsSelected": true
	}
]
},
areasSettings : {
autoZoom : true,
color : "#B4B4B7",
colorSolid : "#84ADE9",
selectedColor : "#84ADE9",
outlineColor : "#666666",
rollOverColor : "#9EC2F7",
rollOverOutlineColor : "#000000"
}
});
</script>