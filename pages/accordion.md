---
layout: simple-page
permalink: /accordion/
breadcrumb: Accordion Test
title: Accordion Test
---

<div id="accordion">
	{%- comment -%} Accordion header {%- endcomment -%}
		<div class="col is-large bp-accordion-header padding has-icons-right field has-addons is-marginless">
			<div class="col is-expanded is-fullwidth is-paddingless">
				<h5 class="has-text-grey-dark is-marginless"><b>Title #1</b></h5>
			</div>
			<span class="sgds-icon sgds-icon-plus is-size-4 bp-accordion-button"></span>
		</div>
	{%- comment -%} Accordion body {%- endcomment -%}
		<div id="accordion-body-1" class="col padding bp-accordion-body">
			<div class="bp-container is-full padding--top--lg padding--bottom" style="width: 100%">
        		<div class="row is-multiline">
					   <div class="col is-4 padding--right--xl padding--bottom">
						<div class="margin--top--none">
							Lorem ipsum
						</div>
					</div>
				</div>
			</div>
		</div>
</div>