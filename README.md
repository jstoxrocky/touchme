# touchme

<h4>Interactive TSG</h4>

<h3>Simple Example</h3>
```python
from touchme import touchme # Import touchme d3sg.js wrapper for IPython notebooks
    
dt = ['2016-01-01', '2016-01-02', '2016-01-03', '2016-01-04', '2016-01-05', '2016-01-06', '2016-01-07', '2016-01-08', '2016-01-09', '2016-01-10', '2016-01-11', '2016-01-12', '2016-01-13', '2016-01-14', '2016-01-15', '2016-01-16', '2016-01-17', '2016-01-18', '2016-01-19', '2016-01-20', '2016-01-21', '2016-01-22', '2016-01-23', '2016-01-24', '2016-01-25', '2016-01-26', '2016-01-27', '2016-01-28', '2016-01-29', '2016-01-30', '2016-01-31', '2016-02-01', '2016-02-02', '2016-02-03', '2016-02-04', '2016-02-05', '2016-02-06', '2016-02-07', '2016-02-08', '2016-02-09', '2016-02-10', '2016-02-11', '2016-02-12', '2016-02-13', '2016-02-14', '2016-02-15', '2016-02-16', '2016-02-17', '2016-02-18', '2016-02-19', '2016-02-20', '2016-02-21', '2016-02-22', '2016-02-23', '2016-02-24', '2016-02-25', '2016-02-26', '2016-02-27', '2016-02-28', '2016-02-29', '2016-03-01', '2016-03-02', '2016-03-03', '2016-03-04', '2016-03-05', '2016-03-06', '2016-03-07', '2016-03-08', '2016-03-09', '2016-03-10', '2016-03-11', '2016-03-12', '2016-03-13', '2016-03-14', '2016-03-15', '2016-03-16', '2016-03-17', '2016-03-18', '2016-03-19', '2016-03-20']
touchy = [60833, 69718, 71671, 66024, 62554, 60096, 56160, 56651, 65558, 62573, 54017, 51915, 51219, 51499, 53289, 60969, 63142, 59018, 57175, 55528, 56180, 56864, 59977, 63261, 59458, 57558, 58583, 56342, 53243, 54222, 54121, 49299, 47826, 46659, 45568, 46342, 51454, 49986, 46075, 46156, 47167, 51218, 52316, 56395, 55882, 53021, 50526, 53524, 52668, 50412, 55693, 56779, 49428, 50114, 49936, 49009, 50699, 61993, 63104, 54663, 47085, 56773, 59308, 52691, 60270, 60163, 55171, 59368, 54523, 57855, 64075, 67899, 58941, 52392, 51251, 54348, 61965, 61220, 67023, 71462]
feely = [38685, 41791, 45100, 39457, 35316, 34585, 34308, 32447, 37182, 40603, 33275, 32337, 31754, 31177, 31136, 36611, 41050, 38313, 34093, 31977, 30926, 32459, 38054, 42084, 34465, 32620, 32349, 31139, 31967, 36445, 40048, 33340, 31473, 30493, 29293, 29796, 34247, 36462, 33216, 32806, 30766, 29669, 29636, 33928, 33978, 35176, 32582, 31827, 30946, 29761, 33080, 36607, 30376, 30564, 30330, 28433, 28587, 34911, 38747, 31352, 28035, 28733, 27730, 27416, 32484, 35346, 28961, 28314, 28562, 28126, 28202, 32141, 34240, 30650, 28776, 28618, 27285, 28050, 32068, 35904]
    
ch = touchme.chart()
ch.line(dt, touchy, 'Touchy')
ch.line(dt, feely, 'Feely')
```

![alt tag](https://rawgit.com/jstoxrocky/touchme/master/touchme/touchme.gif)
