# 全目录

3000套系统，LW，复制到流浪器：www.yuque.com/wisebit/blog
[jQuery Validation Plugin](bassistance.de/jquery-plugins/jquery-plugin-validation/) - Form validation made easy
================================

[![Build Status](https://secure.travis-ci.org/jzaefferer/jquery-validation.png)](travis-ci.org/jzaefferer/jquery-validation)

The jQuery Validation Plugin provides drop-in validation for your existing forms, while making all kinds of customizations to fit your application really easy.

# [Help the project](pledgie.com/campaigns/18159)

[![Help the project](www.pledgie.com/campaigns/18159.png?skin_name=chrome)](pledgie.com/campaigns/18159)

This project is looking for help! [You can donate to the ongoing pledgie campaign](pledgie.com/campaigns/18159)
and help spread the word. If you've used the plugin, or plan to use, consider a donation - any amount will help.

You can find the plan for how to spend the money on the [pledgie page](pledgie.com/campaigns/18159).

# Getting Started

Include jQuery and the plugin on a page. Then select a form to validate and call the `validate` method.

```html
<form>
	<input required>
</form>
<script src="jquery.js"></script>
<script src="jquery.validation.js"></script>
<script>
$("form").validate();
</script>
```

For more information on how to setup a rules and customizations, [check the documentation](docs.jquery.com/Plugins/Validation).

## Contributing
Follow the [jQuery style guide](contribute.jquery.com/style-guides/js), even if existing code doesn't. Add unit tests for any new or changed functionality. Lint and test your code using [grunt](https://github.com/gruntjs/grunt/).

If you've wrote custom methods that you'd like to contribute to additional-methods.js, create a branch, add the method there and send a pull request for that branch.

