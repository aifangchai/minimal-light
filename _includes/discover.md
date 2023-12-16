<!-- Updated HTML with Improved Layout -->

<h2 id="publications" class="section-title">6大發現</h2>

<div class="discover">
  <ol class="bibliography">

    {% for link in site.data.discover.main %}
      <!-- <li class="publication-item"> -->
          <div class="col-sm-9">
            <div class="publication-details">
              <div class="num">{{ link.num }}</div>
              <div class="title">{{ link.title }}</div>
              <div class="description"><em>{{ link.description }}</em></div>
              <br>
            </div>
          </div>

    {% endfor %}

  </ol>
</div>
