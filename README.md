# ПРОТОКОЛ СВЯЗИ С МОДУЛЕМ МИРЫ
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-c3ow" rowspan="4">Запрос/ответ</th>
    <th class="tg-c3ow" colspan="8">Байт</th>
  </tr>
  <tr>
    <th class="tg-c3ow">0</th>
    <th class="tg-c3ow">1</th>
    <th class="tg-c3ow">2</th>
    <th class="tg-c3ow">3</th>
    <th class="tg-c3ow">4</th>
    <th class="tg-c3ow">5</th>
    <th class="tg-c3ow">6</th>
    <th class="tg-c3ow">7</th>
  </tr>
  <tr>
    <th class="tg-0pky" rowspan="2">STRT</th>
    <th class="tg-0pky" rowspan="2">CMD</th>
    <th class="tg-c3ow" colspan="4">Блок данных</th>
    <th class="tg-0pky" rowspan="2">END</th>
    <th class="tg-c3ow" rowspan="2">CS</th>
  </tr>
  <tr>
    <th class="tg-0pky">D[0]</th>
    <th class="tg-0pky">D[1]</th>
    <th class="tg-0pky">D[2]</th>
    <th class="tg-0pky">D[3]</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow" colspan="9">Идентификационный номер модуля миры</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Запрос</td>
    <td class="tg-c3ow">0xA5</td>
    <td class="tg-c3ow">'i'</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">0x5A</td>
    <td class="tg-c3ow">0x00 - 0xFF</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Ответ</td>
    <td class="tg-c3ow">0xA5</td>
    <td class="tg-c3ow">'i'</td>
    <td class="tg-c3ow">b1</td>
    <td class="tg-c3ow">b2</td>
    <td class="tg-c3ow">b3</td>
    <td class="tg-c3ow">b4</td>
    <td class="tg-c3ow">0x5A</td>
    <td class="tg-c3ow">0x00 - 0xFF</td>
  </tr>
</tbody>
</table>
