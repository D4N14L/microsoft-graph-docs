
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const workbookChartPoint = {
};

let res = await client.api('/me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/series/{series-id}/points')
	.post({workbookChartPoint : workbookChartPoint});

```