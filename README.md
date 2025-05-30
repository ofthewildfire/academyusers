# Academy Users Plugin for OctoberCMS

This plugin extends the RainLab.User plugin with additional fields specifically designed for academy members. It adds the following fields to user profiles:

- Organization
- City/State
- Reason for Joining

## Installation

```bash
composer require ofthewildfire/academyusers
```

## Usage

The plugin automatically extends the user profile with additional fields. To display the profile form on your frontend, use the included component:

```twig
{% component 'profileForm' %}
```

## License

This plugin is licensed under the MIT license.
# academyusers
