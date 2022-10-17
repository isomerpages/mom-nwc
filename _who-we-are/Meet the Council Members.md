---

title: Meet the Council Members
permalink: /who-we-are/councilmembers/
breadcrumb: Meet the Council Members
---

## **Members of the National Wages Council 2022/2023**

### **Chairman**
<br>
{% assign board-of-directors = site.data.council-members.chairman %}
<div class="row is-multiline padding--bottom--lg" id="board-of-directors">
  {% for director in board-of-directors %}
    <div class="col is-half person-info-card padding--right">
      <div class="row margin--bottom--xs margin--right">
        <div class="col is-one-third image-col">
          {% if director.image-url %}
            <img class="margin--right--none" src="{{- site.baseurl -}}{{- director.image-url -}}">
          {% endif %}
        </div>
        <div class="col padding--top padding--bottom bg-table-grey">
          <p class="is-marginless padding--top--sm">
            <b>{{- director.name -}}</b><br>
            <small class="is-uppercase" style="font-size: 0.75rem">{{- director.title -}}</small><br>
          </p>
          <h6 class="is-marginless margin--top--xs"><b>{{- director.organisation -}}</b></h6>
        </div>
      </div>
    </div>
  {% endfor %}
</div>

### **Employer Group**
<br>
{% assign board-of-directors = site.data.council-members.employer-group %}
<div class="row is-multiline padding--bottom--lg" id="board-of-directors">
  {% for director in board-of-directors %}
    <div class="col is-half person-info-card padding--right">
      <div class="row margin--bottom--xs margin--right">
        <div class="col is-one-third image-col">
          {% if director.image-url %}
            <img class="margin--right--none" src="{{- site.baseurl -}}{{- director.image-url -}}">
          {% endif %}
        </div>
        <div class="col padding--top padding--bottom bg-table-grey">
          <p class="is-marginless padding--top--sm">
            <b>{{- director.name -}}</b><br>
            <small class="is-uppercase" style="font-size: 0.75rem">{{- director.title -}}</small><br>
          </p>
          <h6 class="is-marginless margin--top--xs"><b>{{- director.organisation -}}</b></h6>
        </div>
      </div>
    </div>
  {% endfor %}
</div>

### **Employee Group**
<br>
{% assign board-of-directors = site.data.council-members.employer-group %}
<div class="row is-multiline padding--bottom--lg" id="board-of-directors">
  {% for director in board-of-directors %}
    <div class="col is-half person-info-card padding--right">
      <div class="row margin--bottom--xs margin--right">
        <div class="col is-one-third image-col">
          {% if director.image-url %}
            <img class="margin--right--none" src="{{- site.baseurl -}}{{- director.image-url -}}">
          {% endif %}
        </div>
        <div class="col padding--top padding--bottom bg-table-grey">
          <p class="is-marginless padding--top--sm">
            <b>{{- director.name -}}</b><br>
            <small class="is-uppercase" style="font-size: 0.75rem">{{- director.title -}}</small><br>
          </p>
          <h6 class="is-marginless margin--top--xs"><b>{{- director.organisation -}}</b></h6>
            <small class="is-uppercase" style="font-size: 0.75rem">{{- director.title2 -}}</small><br>
          </p>
          <h6 class="is-marginless margin--top--xs"><b>{{- director.organisation2 -}}</b></h6>
        </div>
      </div>
    </div>
  {% endfor %}
</div>

### **Government Group**
<br>
{% assign board-of-directors = site.data.council-members.employer-group %}
<div class="row is-multiline padding--bottom--lg" id="board-of-directors">
  {% for director in board-of-directors %}
    <div class="col is-half person-info-card padding--right">
      <div class="row margin--bottom--xs margin--right">
        <div class="col is-one-third image-col">
          {% if director.image-url %}
            <img class="margin--right--none" src="{{- site.baseurl -}}{{- director.image-url -}}">
          {% endif %}
        </div>
        <div class="col padding--top padding--bottom bg-table-grey">
          <p class="is-marginless padding--top--sm">
            <b>{{- director.name -}}</b><br>
            <small class="is-uppercase" style="font-size: 0.75rem">{{- director.title -}}</small><br>
          </p>
          <h6 class="is-marginless margin--top--xs"><b>{{- director.organisation -}}</b></h6>
        </div>
      </div>
    </div>
  {% endfor %}
</div>
