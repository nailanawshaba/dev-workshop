# Site wide customization

Now we can make some changes that will apply to the whole site.
We can add a `Geocollections`entry in the top menu bar.

Edit the `site_base.html`file in the templates folder and uncomment the list item adapting the text as well.

{% raw %}

```html
{% block extra_tab %}
<li>
 <a href="geocollections">Geocollections</a>
</li>
{% endblock %}
```

{% endraw %}

On browser refresh you will see a new entry in the nav bar which is persistent to the whole site.
