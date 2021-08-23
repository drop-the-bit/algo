## Algo
알고리즘 공부용 Repo

## test
{% for col in site.collections %}
  {{col.relative_directory}}
{% endfor %}

## Solutions
{% for ms in site.moosung %}
<details>
      <summary>
      무성      
      </summary>
      {{ms.name}}
</details>

{% endfor %}

