# response format


### install
>$ npm install --save res-format


[![npm version](https://badge.fury.io/js/res-format.svg)](http://badge.fury.io/js/res-format)

### Usage
>var  var response = new Response();

>response.format({code:'00000',message:'something',data:[]});

<<<<<<< HEAD
    {"code":"00000","data":[],"status":"success","message":"something","time":1479172147579}
=======
	{"code":"00000","data":[],"status":"success","message":"something","time":1479172147579}
>>>>>>> cf048667132b4fb3fd1e2935917c876d80d4acd8

>response.format({code:'10010',message:'something',data:[]});

    {"code":"10010","data":[],"status":"create failed","message":"something","time":1479172188430}

>response.format({code:'10020',message:'something',data:[]});

    {"code":"10020","data":[],"status":"insert  failed","message":"something","time":1479172199972}
<<<<<<< HEAD
        
>response.format({code:'10030',message:'something',data:[]});

    {"code":"10030","data":[],"status":"update  failed","message":"something","time":1479172385525}
    
>response.format({code:'10040',message:'something',data:[]});

    {"code":"10040","data":[],"status":"update  failed","message":"something","time":1479172385525}

>response.format({code:'10050',message:'something',data:[]});

    {"code":"10050","data":[],"status":"update  failed","message":"something","time":1479172385525}
    

>response.format({code:'99999',message:'something',data:[]});

    {"code":"99999","data":[],"status":"update  failed","message":"something","time":1479172385525}
=======
		
>response.format({code:'10030',message:'something',data:[]});

	{"code":"10030","data":[],"status":"update  failed","message":"something","time":1479172385525}
	
>response.format({code:'10040',message:'something',data:[]});

	{"code":"10040","data":[],"status":"update  failed","message":"something","time":1479172385525}

>response.format({code:'10050',message:'something',data:[]});

	{"code":"10050","data":[],"status":"update  failed","message":"something","time":1479172385525}
	

>response.format({code:'99999',message:'something',data:[]});

	{"code":"99999","data":[],"status":"update  failed","message":"something","time":1479172385525}
>>>>>>> cf048667132b4fb3fd1e2935917c876d80d4acd8

### setting

>response.setCode('00000','ok');

>response.format({code:'00000',message:'something',data:[]});

<<<<<<< HEAD
    {"code":"00000","data":[],"status":"ok","message":"something","time":1479172676144}
=======
	{"code":"00000","data":[],"status":"ok","message":"something","time":1479172676144}
>>>>>>> cf048667132b4fb3fd1e2935917c876d80d4acd8
