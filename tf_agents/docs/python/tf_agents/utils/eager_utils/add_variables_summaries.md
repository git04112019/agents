<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf_agents.utils.eager_utils.add_variables_summaries" />
<meta itemprop="path" content="Stable" />
</div>

# tf_agents.utils.eager_utils.add_variables_summaries

<table class="tfo-notebook-buttons tfo-api" align="left">
</table>

<a target="_blank" href="https://github.com/tensorflow/agents/tree/master/tf_agents/utils/eager_utils.py">View
source</a>

Add summaries for variables.

``` python
tf_agents.utils.eager_utils.add_variables_summaries(
    grads_and_vars,
    step
)
```

<!-- Placeholder for "Used in" -->

#### Args:

* <b>`grads_and_vars`</b>: A list of (gradient, variable) pairs.
* <b>`step`</b>: Variable to use for summaries.