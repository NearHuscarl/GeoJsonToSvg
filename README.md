# GeoJsonToSvg

Anh clone về, build rồi mở vào endpoint này test thử. Dữ liệu test [tại đây](https://github.com/NearHuscarl/GeoJsonToSvg/blob/e554f91add3778805bd57365e98181d56b73ea51/Controllers/SvgController.cs#L57-L76)

```
https://localhost:[port]/svg?geojson={\%22type\%22:%20\%22LineString\%22,\%22coordinates\%22:[[577750,1153651],[578897,1155848]]}
```

Nó sẽ trả về svg string

```
<?xml version="1.0" encoding="utf-8"?><svg xmlns="http://www.w3.org/2000/svg" version="1.1" baseProfile="tiny" width="350" height="350" viewBox="0 0 350 350"><g><g stroke="#000000" stroke-width=".98" fill="none"><path d="m83.64 350l182.72-350" /></g></g></svg>
```
