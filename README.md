







-


     
"         
          #  

XXXXXXXXXXXXXXXXXXXXXXXXXXXX"
n {kn}"}


---------------------------
CE (quickest way t get the ole repo)
# ----------------------------
l = f"https://api.github.com/repos/{owner}/{repo}/zipball/{branch}"
(z_url, hs=hea


# Unpack the zip into a local folder
zip_bytes = io.BytesIO(resp.content)
 zipfile.ZipFile(zip_bytes) as z:
    # The zip contains a top‑level folder like "owner-repo-<hash>"
    # Extract everything into a folder named after the repo
    extract_path = f"./{repo}"
    os.makedirs(extract_path, exist_ok=True)
   

print(f"✅  Repository '{owner}/{repo}' extracted to ./{repo}")
.

