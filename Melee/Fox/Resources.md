## Resource Compilations
- [Fox cookbook](https://cookbook.gg/fox)

## TODO
```dataview
LIST
FROM #todo AND #fox
```

## Insights
```dataview
LIST
FROM #fox AND (#insights OR #thoughts)
WHERE relevance>5
```

## Vods
```dataview
LIST 
FROM #vods and #fox 
```