# satel-pr-slack-notifier
This centralized GitHub action notifies devs on slack about the comments on their PR

## Usage
```YAML
    - name: Run PR commenter
      uses: SatelCreative/satel-pr-slack-notifier@1.0.0
      with: 
        SLACK_API_TOKEN: ${{ secrets.SLACK_API_TOKEN }}
        SLACK_WEBHOOK_URL: ${{ secrets.SLACK_WEBHOOK_URL }}
```