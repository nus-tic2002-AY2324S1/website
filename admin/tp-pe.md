{% from "common/macros.njk" import embed_topic with context %}
{% from "common/admin.njk" import show_admin_page with context %}

{% call show_admin_page("tp-pe") %}
<div id="main">

### <div class="text-white bg-success p-1">tP: Practical Exam (PE)</div>
<div id="tp-practicalexam">
<include src="tp-pe-fragment.md" />
</div>

</div>

{% endcall %}
