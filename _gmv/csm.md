---
title : 'Result of CSM'
toc : true
toc_sticky : true
---

---

# GoC단위의 Box Result

계약 집합 단위에서 금액이 확정되는 CSM 이나 Loss 및 직접신계약비 (DAC) 항목은 개별 CF단위에서 산출한 결과를 바탕으로 GoC (계약집합) level에서 집계된 금액의 부호 및 손실요소 배부비율 등을 결정할 수 있다.

## CSM

## Loss

asfasdfas
asdfasd
asdfas
aasdf
손실요소가 발생한 GoC의 손실요소 추적관련 처리사항. 신계약의 비용인식,  손실요소 배부, 손실환입(전입)
{: .notice--success}


## DAC



# References
<ul>

{% for member in site.data.test %}
  <!-- <li>
    <a href="#goc단위의-box-result">
      {{ member.para }}
    </a>
  </li> -->
  {% capture desc %}
       {{ member.desc }}
  {% endcapture %}

  
  ## {{ member.id }}. {{ member.para }} 
  
  {{ desc | markdownify}}
{% endfor %}
 </ul> 

# v2

<ul>

{% for member in site.data.test %}
 
  {% capture desc %}
       {{ member.desc }}
  {% endcapture %}

  {% capture temp %}
    ## {{ member.id }}. {{ member.para }} 
  {% endcapture %}
  
  
   <h2>{{ member.id }}. {{ member.para }} </h2>
  {{temp | markdownify}}
   
  {{ desc | markdownify}}
  
{% endfor %}
 </ul> 


