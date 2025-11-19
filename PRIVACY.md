# Privacy Policy

## Privacy Notice

**No personal data is collected or stored by this GitHub Action.** This Action only processes your Kedro project files locally within the GitHub Actions runner environment to generate static visualization artifacts.

## Data Processing Summary

- **Data Processed**: Kedro project configuration files, pipeline definitions, and metadata
- **Processing Location**: GitHub Actions runner (ephemeral environment)
- **Data Storage**: No persistent data storage by this Action
- **Data Transmission**: Only static HTML/JS/CSS artifacts uploaded to GitHub Pages

## Telemetry and Opt-Out

This Action includes an optional telemetry feature that can send usage data to Kedro Org:

- **Default Setting**: Telemetry is **disabled by default** (`telemetry_consent: false`)
- **Opt-In Required**: You must explicitly set `telemetry_consent: true` to enable
- **Data Sent**: Anonymous usage statistics about Kedro-Viz features used
- **Opt-Out Instructions**: Keep `telemetry_consent: false` (default) or omit the parameter

### How to Disable Telemetry Explicitly

```yaml
- uses: kedro-org/publish-kedro-viz@v3
  with:
    telemetry_consent: false  # Explicitly disable (default)
```

## GDPR/CCPA Compliance

This Action complies with GitHub's Data Protection Addendum and applicable data protection regulations:

- No personal data collection or processing
- No cookies or tracking mechanisms
- No data retention beyond GitHub Actions job execution
- Processing limited to generating static visualizations

## Data Controller Information

**Organization**: Kedro Community (kedro-org)  
**Contact**: kedro-framework@mckinsey.com  
**Purpose**: Data pipeline visualization and documentation  

## Your Rights

Under applicable data protection laws, you have the following rights:

- **Right to Information**: This privacy policy provides information about our data processing
- **Right to Access**: You can request information about any data processing (though we process no personal data)
- **Right to Rectification**: You can request correction of inaccurate data (not applicable as we process no personal data)
- **Right to Erasure**: You can request deletion of personal data (not applicable as we process no personal data)
- **Right to Object**: You can object to data processing by not using this Action or disabling telemetry

## Third-Party Services

This Action uses the following third-party services:

### GitHub Actions Platform
- **Service**: GitHub Actions runner environment
- **Data Shared**: Repository contents during workflow execution
- **Privacy Policy**: [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement)

### GitHub Pages
- **Service**: Static website hosting
- **Data Shared**: Generated HTML/JS/CSS artifacts
- **Privacy Policy**: [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement)

### Kedro-Viz Telemetry (Optional)
- **Service**: Anonymous usage analytics (only if explicitly enabled)
- **Data Shared**: Anonymous feature usage statistics
- **Control**: Disabled by default, requires explicit opt-in

### Third-Party GitHub Actions

This Action integrates with the following third-party GitHub Actions:

#### actions/upload-pages-artifact
- **Author**: GitHub (actions organization)
- **Purpose**: Upload build artifacts for GitHub Pages deployment
- **Data Shared**: Generated static website files (HTML/JS/CSS)
- **License**: MIT
- **Repository**: [actions/upload-pages-artifact](https://github.com/actions/upload-pages-artifact)

#### actions/deploy-pages
- **Author**: GitHub (actions organization)  
- **Purpose**: Deploy artifacts to GitHub Pages
- **Data Shared**: Build artifacts for website deployment
- **License**: MIT
- **Repository**: [actions/deploy-pages](https://github.com/actions/deploy-pages)

#### peaceiris/actions-gh-pages (v1 only)
- **Author**: peaceiris
- **Purpose**: Deploy static site to GitHub Pages branch (legacy v1 functionality)
- **Data Shared**: Generated static website files
- **License**: MIT  
- **Repository**: [peaceiris/actions-gh-pages](https://github.com/peaceiris/actions-gh-pages)
- **Note**: Used only in v1 of this Action for branch-based deployments

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be reflected in the repository commit history and users will be notified through:

- Updates to this PRIVACY.md file
- Release notes for new versions
- Repository announcements for significant changes

## Contact

For questions about data protection or this privacy policy:

- **Email**: kedro-framework@mckinsey.com
- **Security Issues**: See [SECURITY.md](SECURITY.md)
- **General Support**: See [SUPPORT.md](SUPPORT.md)

---

**Last Updated**: November 19, 2024  
**Version**: 1.0