{% from "common/macros.njk" import embed_topic, show_admin_sections_to_read, show_as_tab, thumb, timing_badge with context %}
{% from "common/admin.njk" import policies, show_admin_summary, topics with context %}

{% call show_admin_summary() %}
1. Submit weekly quiz
1. Submit weekly exercises
1. Submit weekly project increments `Level 10. Use More Classes`, `Level 11. Use Multiple Code Files`
{% endcall %}


#### {{ thumb(1) }} Submit weekly quiz

* As usual


#### {{ thumb(2) }} Submit weekly exercises

* As usual


#### {{ thumb(3) }} Submit weekly project increments

<span id="week9-project">

<include src="montyFragment.md" boilerplate var-displacement="../.." var-header="**Level 10. Use More Classes**" var-fragment="monty-fragment.md#monty10" />

<p/>

* ==After submitting the above increment, there is no need to submit subsequent project increments (i.e., Level 11 onwards) on Coursemology.==

<include src="montyFragment.md" boilerplate var-displacement="../.." var-header="**Level 11. Use Multiple Code Files**" var-fragment="monty-fragment.md#monty11" />
</span>
