{% from "common/macros.njk" import embed_topic, show_admin_sections_to_read, show_as_tab, thumb, timing_badge with context %}
{% from "common/admin.njk" import policies, show_admin_summary, topics with context %}

{% call show_admin_summary() %}
1. Submit weekly quiz
1. Do weekly project increments: Add `Level 14. Add a GUI` or the individual feature.
{% endcall %}


#### {{ thumb(1) }} Submit weekly quiz

* As usual

#### {{ thumb(2) }} Do weekly project increments

<span id="week11-project">

* **Option 1:** Add the following project increment.<br>
  {{ icon_info }} This is option is the harder of the two options; it's meant for students who wish to push harder in the project or who wish to learn GUI programming in particular.

<include src="montyFragment.md" boilerplate var-displacement="../.." var-header="**Level 14. Add a GUI**" tag="optional" var-fragment="monty-fragment.md#monty14" />
<p/>

* **Option 2: Add the allocated individual feature.**
  * Note that ==a very minimal implementation of the feature is good enough==.
  * Steps to find the feature you should implement:
    * First, take the last digit of your student number. For example, if your student number is `A0123456H`, the last digit is `6`.
    * Then, find the matching row in the table below. That row gives you three choices.
    * You may implement any one of the three choices. Click on the link to find details of the feature.
    * The expected amount of work for this option is about 1/4 to 1/3 of the amount of code you have written so far in the project.

<div class="indented-level4" id="feature-allocation">

{% macro ilink(increment) %}[{{ increment }}](../../programming/chapters/monty.html#{{ increment | lower }}){% endmacro %}

digit | choice 1                             | choice 2                            | choice 3
------|--------------------------------------|-------------------------------------|-------------------------
0     | {{ ilink('C-Update') }}              | {{ ilink('C-DetectDuplicates') }}   | {{ ilink('C-Statistics') }}
1     | {{ ilink('C-Tagging') }}             | {{ ilink('C-FlexibleDataSource') }} | {{ ilink('C-FriendlierSyntax') }}
2     | {{ ilink('C-Priority') }}            | {{ ilink('C-DateTimes') }}          | {{ ilink('B-DoWithinPeriodTasks') }}
3     | {{ ilink('C-Archive') }}             | {{ ilink('C-Sort') }}               | {{ ilink('B-Events') }}
4     | {{ ilink('C-MassOps') }}             | {{ ilink('C-Search') }}             | {{ ilink('B-FixedDurationTasks') }}
5     | {{ ilink('C-Statistics') }}          | {{ ilink('C-Update') }}             | {{ ilink('C-DetectDuplicates') }}
6     | {{ ilink('C-FriendlierSyntax') }}    | {{ ilink('C-Tagging') }}            | {{ ilink('C-FlexibleDataSource') }}
7     | {{ ilink('B-DoWithinPeriodTasks') }} | {{ ilink('C-Priority') }}           | {{ ilink('C-DateTimes') }}
8     | {{ ilink('B-Events') }}              | {{ ilink('C-Archive') }}            | {{ ilink('C-Sort') }}
9     | {{ ilink('B-FixedDurationTasks') }}  | {{ ilink('C-MassOps') }}            | {{ ilink('C-Search') }}
</div>

</span>
