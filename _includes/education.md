<h2 id="education" style="margin: 2px 0px -15px;">Education</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.education.main %}
<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if link.image %} 
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="school">{{ link.school }}</div>
      <div class="degree">Degree: {{ link.degree }}</div>
      <div class="major">Major: {{ link.major }}</div>
      <div class="year">Year: {{ link.year }}</div>
      <div class="GPA">GPA: {{ link.GPA }}</div>
  </div>
</div>
<br>
{% endfor %}

</ol>
</div>
