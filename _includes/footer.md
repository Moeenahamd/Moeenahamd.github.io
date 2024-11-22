    <footer>
      <hr>
      <div class="navbar">
        <a href="mailto:opensourcereartwork@gmail.com" target="_blank">Email</a>
        <a href="https://github.com/opensourceartists" target="_blank">Github</a>
        <a href="https://instagram.com/opensourceartists" target="_blank">Instagram</a>
        <a href="/" target="_blank">Portfolio</a>
      </div>
      <br />
      This blog is <a href="{{ site.repo.repository_url }}">open source</a>.
      See an error? Go ahead and
      <a href="{{ site.repo.repository_url }}/edit/{{ site.repo.branch }}/{{ page.path }}" title="Help improve {{ page.path }}">propose a change</a>.
      <br />
      <img style="padding-top: 5px;" src="/assets/img/banner.png" />
      <a href="https://notbyai.fyi/"><img style="padding-top: 5px;" src="/assets/img/notbyai.svg" /></a>
    </footer>
    <!-- Workaround for FB MITM -->
    <span id="iab-pcm-sdk"></span><span id="iab-autofill-sdk"></span>
    {% include analytics.md %}
