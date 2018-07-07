# Widger Label
versi: 1  
css: bootstrap  

```xml
<b:widget id='Label5' locked='false' title='Label' type='Label' version='1'>
  <b:widget-settings>
    <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
    <b:widget-setting name='display'>LIST</b:widget-setting>
    <b:widget-setting name='selectedLabelsList'/>
    <b:widget-setting name='showType'>ALL</b:widget-setting>
    <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
  </b:widget-settings>
  <b:includable id='main'>
    <b:class name='row'/>
    <b:loop values='data:labels' var='label'>
      <b:if cond='data:label.name == &quot;Heru Sularto (eR)&quot;'>
        <div class='col'>
          <h4><a expr:href='data:blog.homepageUrl + &quot;search/label/Heru%20Sularto%20(eR)&quot;'>Heru Sularto (eR)</a></h4>
          <p>Sampai saat ini aku baru bisa menjelaskan <data:label.count/> hal tentang diriku.</p>
        </div>
      </b:if>
      <b:if cond='data:label.name == &quot;Kehidupanku&quot;'>
        <div class='col'>
          <h4><a expr:href='data:blog.homepageUrl + &quot;search/label/Kehidupanku&quot;'>Kehidupanku</a></h4>
          <p>Ada <data:label.count/> kisah dalam hidupku yang aku tak sanggup untuk tidak menuliskannya.</p>
        </div>
      </b:if>
      <b:if cond='data:label.name == &quot;Sahabat&quot;'>
        <div class='col'>
          <h4><a expr:href='data:blog.homepageUrl + &quot;search/label/Sahabat&quot;'>Sahabatku</a></h4>
          <p>Saat ini baru bisa memuat <data:label.count/> tulisan mengenai sahabatku. Apakah kamu ada di situ? Jika belum, maafkanlah aku.</p>
        </div>
      </b:if>
      <b:if cond='data:label.name == &quot;Nasehat&quot;'>
        <div class='col'>
          <h4><a expr:href='data:blog.homepageUrl + &quot;search/label/Nasehat&quot;'>Nasehatnya</a></h4>
          <p>Bacalah nasehatnya, syukur-syukur <data:label.count/> nasehat yang ada kamu baca semuanya.</p>
        </div>
      </b:if>
      <b:if cond='data:label.name == &quot;Garapan&quot;'>
        <div class='col'>
          <h4><a expr:href='data:blog.homepageUrl + &quot;search/label/Garapan&quot;'>Garapanku</a></h4>
          <p>Dari <data:label.count/> garapan yang ada, sebagian sudah selesai dan sebagian belum.</p>
        </div>
      </b:if>
      <b:if cond='data:label.name == &quot;Blogger&quot;'>
        <div class='col'>
          <h4><a expr:href='data:blog.homepageUrl + &quot;search/label/Blogger&quot;'>Blogger Tips</a></h4>
          <p>Ada <data:label.count/> tulisan yang membahas trik dan tips Blogger. Yuk disimak.</p>
        </div>
      </b:if>
    </b:loop>
  </b:includable>
</b:widget>
```
