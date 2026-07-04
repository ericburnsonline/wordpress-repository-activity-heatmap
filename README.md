# Repository Activity Heatmap for WordPress

A WordPress plugin that displays a repository commit activity heatmap.

The plugin is intended to create a compact, GitHub-style activity grid for a specific source-code repository. It can be embedded on WordPress pages or posts with a shortcode and will refresh its activity data on a regular schedule.

## Planned Features

* Display commit activity by day in a heatmap grid
* Support public repositories
* Accept a repository name such as `owner/repository`
* Optional start date and author filters
* Cache activity data in WordPress
* Refresh repository activity once per day
* Provide a shortcode for embedding the heatmap in posts and pages
* Gracefully handle missing repositories, API errors, and rate limits

## Planned Shortcode

```text
[repo_activity_heatmap repo="owner/repository"]
```

Example with optional settings:

```text
[repo_activity_heatmap
  repo="owner/repository"
  start_date="2026-01-01"
  author="GitHubUsername"
]
```

## Status

Early development. The repository currently contains project setup files only.

## License

This project is licensed under the MIT License. See `LICENSE` for details.
