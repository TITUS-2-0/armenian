

### Unit Mapping
The TITUS 1 structural units are mapped onto TEI as follows:

| Source Unit | TEI Mapping | Notes |
|-------------|-------------|-------|
| Chapter | `div@chapter` | Automatically translated into named div |
| Page | `pb` |  |
| Line | `lb` |  |

### Structural overview
```text
text (@xml:lang=xcl-Armn)
  front (@xml:id)
    titlePage (@xml:id)
      docTitle (@xml:id)
        titlePart (@xml:id)
  body
    p (@xml:id)
      [lb (@n) (multiple)]
    div (@data-level=1, @n, @type=chapter, @xml:id) (multiple)
      p (@xml:id) (multiple)
        [lb (@n) (multiple)]
        [pb (@n) (multiple)]
      [pb (@n) (multiple)]
    [pb (@n)]
```

### Structure Example

```xml
<div xmlns="http://www.tei-c.org/ns/1.0" n="1" xml:id="chapter-1" type="chapter" data-level="1">
				<p xml:id="chapter-1-p-2">
					<lb n="8"/>ԶԱԶՔԱՆԱԶԵԱՆ2 Ազգին եւ զՀայաստան աշխարհին զաստուածա\պարգեւ<lb n="9"/>գրոյն, եթէ ե́րբ եւ յորում ժամանակի մատակարարեցաւ եւ<lb n="10"/>որպիսի' արամբ այնպիսի նորոգատուր աստուածեղէն շնորհս երեւեցաւ<lb n="11"/>եւ վասն նորին լուսաւոր վարդապետութեան եւ հրեշտակաբար կրաւնիցն<lb n="12"/>առաքինութեան զմտաւ ածելով յիշատակարանս առանձին մատենա\նշան<lb n="13"/>ծաղկեցուցանել եւ մինչ դեռ անդէն ի խորհրդանոցի մտացս վասն<lb n="14"/>յուշ արկանելոյ միայնագործ հոգայի, եկեալ հասանէր առ իս հրաման<lb n="15"/>առն միոյ պատուականի Յովսեփ կոչեցելոյ, աշակերտի առն այնորիկ,<lb n="16"/>եւ ընդ նմին այլոց եւս քաջալերութիւն աշակերտակցաց մերոյն վար\դապետութեան։<lb n="17"/>Ուստի եւ իմ մասնաւոր աշակերտութեան վիճակ առեալ,<lb n="18"/>թէպէտ եւ էի կրսերագոյն, եւ առաւել քան զկար մեր, գրաւեալ անաչառ<lb n="19"/>հրամանին հասելոյ, փութանակի եւ առանց յապաղելոյ զառաջի եղեալն<pb n="24"/>
					<lb n="1"/>մատենագրել։ Զորս եւ մեր համաւրէն աղաչեալ երկախառնել ընդ մեզ<lb n="2"/>աղաւթիւնք՝ յանձնարարութեամբ աստուածեղէն շնորհացն, զի կամակա\րագոյնս<lb n="3"/>եւ ուղղագոյնս նաւիցեմք զհամատարած ալեաւքն վարդապետա\կան<lb n="4"/>ծովուն։</p>
			</div>
```
