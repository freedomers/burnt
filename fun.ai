def get_data(url):
    response = requests.get(url, headers=headers)
    response.encoding = 'utf-8'
    selector = etree.HTML(response.text)
    content = selector.xpath('//*[@id="newpcnews-1"]/div/div[2]/a[1]/div/text()')  
    print(content)
