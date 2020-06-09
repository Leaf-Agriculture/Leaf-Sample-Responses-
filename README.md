Here you can find an example response from Leaf's Machine Data API. 
The response contains the original file, conversion files, data translated into a unified machine data model, rendered images of the operation, summary data of the operation, polygon of the area, and more. We've added each file generated in this repository for easy viewing.

For our quickstart Postman collection, go to https://github.com/Leaf-Agriculture/Leaf-quickstart-Postman-collection  

Our docs are available at https://dev.agrigate.io/#introduction



Example response from Leaf's API:

``` json
{
  "id": "c06ad9c0-38b7-4d03-8182-4979352636a1",
  "fileName": "Export From MyJohnDeere - Seeding.zip",
  "providerFileId": "25347351824",
  "providerName": "JohnDeere",
  "providerId": 2,
  "originalUrl": "https://leaf-jd-files.s3.us-west-2.amazonaws.com/output/None/25347351824/Export From MyJohnDeere - Seeding.zip",
  "rawGeojsonUrl": "https://converter-prd-conversionsbucket-1oq1gn85k16lk.s3.us-west-2.amazonaws.com/a9795db0-f015-4964-8e80-55be40cb3e90.json",
  "status": "CONVERTED",
  "stdGeojsonUrl": "https://converter-prd-conversionsbucket-1oq1gn85k16lk.s3.us-west-2.amazonaws.com/9753076c-5a54-4026-8820-58079564fb49.json",
  "pngUrl": "https://converter-prd-conversionsbucket-1oq1gn85k16lk.s3.us-west-2.amazonaws.com/4128678e-af5c-4087-9217-b33da2f1e2f3.zip",
  "leafUserId": "",
  "apiOwnerUsername": "",
  "fileType": "PRESCRIPTION",
  "convertedTime": "2020-05-29T17:47:56.138",
  "createdTime": "2020-05-29T17:46:12.981",
  "startTime": "2016-04-23T14:32:04.2",
  "endTime": "2016-04-24T02:05:56.357",
  "sizeInBytes": 1303789,
  "summary": {
    "type": "Feature",
    "properties": {
      "totalDistance": 434846.56728705624,
      "elevation": {
        "mean": 772.1939917812882,
        "stdDev": 1.2011308801115006,
        "min": 767.21031609,
        "max": 775.38288827
      },
      "crop": [
        "soybeans"
      ],
      "startTime": "2016-04-23T14:32:04.200000+00:00",
      "endTime": "2016-04-24T02:05:56.357000+00:00",
      "operationProperties": {
        "appliedRate": {
          "mean": 139693.05106259603,
          "stdDev": 1164.069468895998,
          "min": 136718.99737436,
          "max": 142336.03408865
        }
      },
      "operationType": "PLANTED",
      "totalArea": 103032.038038834
    },
    "geometry": {
      "coordinates": [
        [
          [
            [-93.15284855410137,41.66614932626991],
            [-93.15290112549427,41.66615083975181],
            [-93.15291200300813,41.66615212569288],
            [-93.15294254848251,41.66616728251823],
            [-93.15335720692175,41.66663184875443],
            [-93.15337552342606,41.66665374811262],
            [-93.15339226065771,41.666675233957555],
            [-93.153407898004,41.66669751514099],
            [-93.15342277326258,41.66671919171038],
            [-93.15343719601022,41.66674049918784],
            [-93.15345144674309,41.66676216198029],
            [-93.15346513465991,41.66678341342522],
            [-93.15349222683513,41.6668270393644],
            [-93.15385006006868,41.66740750264258],
            [-93.15386333314646,41.66742920797033],
            [-93.15430414116321,41.668164104694036],
            [-93.15434227218078,41.66822988159492],
            [-93.15442892585408,41.66838227651283],
            [-93.15444136285711,41.66840427695543],
            [-93.1544783240199,41.66847015967233],
            [-93.15452656091362,41.66855775113196],
            [-93.15456203438673,41.66862399701901],
            [-93.15457335576912,41.66864628490395],
            [-93.15459605955442,41.66869105073903],
            [-93.1546743778587,41.66884611637062],
            [-93.15469678201234,41.66889156294842],
            [-93.1547074583096,41.66891406529799],
            [-93.1547178779054,41.66893710816884],
            [-93.15475564861826,41.669028915954044],
            [-93.15477443387208,41.669075484545424],
            [-93.15478346918536,41.66909914946927],
            [-93.15479196396802,41.66912250667538],
            [-93.1547999474517,41.66914663233633],
            [-93.15480725324882,41.66917097370584],
            [-93.15481390744115,41.66919636569432],
            [-93.15481847403525,41.669223585842616],
            [-93.15482015627475,41.66925220974141],
            [-93.15481745221227,41.66928229122556],
            [-93.15480986087282,41.66931056868151],
            [-93.15479880222051,41.66933813762509],
            [-93.15478273586437,41.669364977564605],
            [-93.15476180700036,41.66939082321938],
            [-93.15473656247208,41.66941380568529],
            [-93.15470767031866,41.66943293237633],
            [-93.15467581335173,41.6694496057003],
            [-93.15464226841964,41.66946346103699],
            [-93.15460743744586,41.66947457432028],
            [-93.15457146913438,41.669482938843956],
            [-93.15453427010878,41.66948796938737],
            [-93.15449797711273,41.66949106893197],
            [-93.15446077616512,41.66949121455876],
            [-93.15442516463929,41.66948931861102],
            [-93.15432927513885,41.66947819346348],
            [-93.15429651381895,41.66947408573326],
            [-93.15426416614899,41.669469611674266],
            [-93.15423248431355,41.66946506804719],
            [-93.15386148010982,41.66941128134546],
            [-93.153768736235,41.66939777020012],
            [-93.1534585875594,41.66935257241183],
            [-93.15339469962416,41.66934321044096],
            [-93.15336377203931,41.66933825202178],
            [-93.1532084628096,41.669312787527616],
            [-93.15317727690828,41.66930748966999],
            [-93.15311459260097,41.669296501652575],
            [-93.15274586201006,41.66923037522995],
            [-93.15219214784669,41.66912769937019],
            [-93.15216137646216,41.66912183175014],
            [-93.15182398809434,41.669056979105456],
            [-93.1517618587881,41.66904482987113],
            [-93.15173110415569,41.669038618937385],
            [-93.15072272634414,41.66883270531196],
            [-93.15066127921968,41.66881979639373],
            [-93.15062873152533,41.66881258261262],
            [-93.15059905964756,41.66880579412083],
            [-93.15057167395054,41.66879879549235],
            [-93.15054745957035,41.66879226579332],
            [-93.15052421037454,41.66878525007401],
            [-93.15050165220019,41.668778170027984],
            [-93.15047945218697,41.66877018426264],
            [-93.15045740103263,41.66876180342803],
            [-93.15043500967803,41.66875233017803],
            [-93.15041194042519,41.66874134599985],
            [-93.15038961986767,41.66872929695463],
            [-93.15036837561854,41.66871544802352],
            [-93.15034847356921,41.66869991771248],
            [-93.15034073196121,41.66869291463927],
            [-93.1503035863441,41.668641584866236],
            [-93.15029674122553,41.668620027393914],
            [-93.15029224238613,41.66859957049258],
            [-93.15027068023227,41.66833419123326],
            [-93.15026905529253,41.66831335233188],
            [-93.15026780367309,41.668292661607104],
            [-93.15025117558098,41.66651320515659],
            [-93.15025098938469,41.66649027579174],
            [-93.15025178692737,41.66646680999609],
            [-93.15025332073638,41.666443917302885],
            [-93.15025559884032,41.66642238672031],
            [-93.15025969752263,41.66640071032482],
            [-93.15026490656734,41.666378922653664],
            [-93.15027233999825,41.66635754989695],
            [-93.15028117908888,41.66633501849981],
            [-93.15029396294024,41.666311784301065],
            [-93.1503105442941,41.66629030071683],
            [-93.15033038038312,41.666270973041065],
            [-93.15035271903473,41.66625325000885],
            [-93.15037633622427,41.666238009056975],
            [-93.15040236586148,41.666224044006185],
            [-93.15043232138171,41.666211642832906],
            [-93.15046493055145,41.66620225858091],
            [-93.15049897008163,41.66619742595536],
            [-93.15133940006966,41.66616354088279],
            [-93.1513459720544,41.666163297141516],
            [-93.15284855410137,41.66614932626991]
          ]
        ]
      ],
      "type": "MultiPolygon"
    }
  }
}
```
