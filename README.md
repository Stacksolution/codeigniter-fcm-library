# codeigniter-fcm-library
This library use for single and multiple notification send at a time 

#load library and use for single notification
`$this->load->library('fcm/Notification','notification');`
`$config['notification_serverkey']  = 'AAAAF3VEsPU:APA91bGhj1QxN9TW-p24f8yxnUC7FHD0xq043w81gi1y1weCqb21Nv35GZWiJoT-4InHM_lJOKBpVBL0D4kF67yKt1ouO_TWmH--QHS_axIB6CnFh0UALsQr6NTj5ooPWglPyLP35NQR';`
`$this->notification->initialize($config);`
`$this->notification->subject("Hello");`
`$this->notification->message("Hello i am adil");`
`$this->notification->send("fZP16uRHQCWfJ2j2_c6_P3:APA91bEbRzB3gexlOVYm1i1qyPGnfc8U02EoB9-v2F7XvbHiCGIk-ry-7Eoelwhlt4wRwRZgP722WhLzfoKIFmOFBLYi0FjYjP7-QdPr0Sx_HDuGG2jIlx-A2C_XiWHhV0FObPYd1qA0");
`

#load library and use for multiple notification
`$this->load->library('fcm/Notification','notification');`
`$config['notification_serverkey']  = 'AAAAF3VEsPU:APA91bGhj1QxN9TW-p24f8yxnUC7FHD0xq043w81gi1y1weCqb21Nv35GZWiJoT-4InHM_lJOKBpVBL0D4kF67yKt1ouO_TWmH--QHS_axIB6CnFh0UALsQr6NTj5ooPWglPyLP35NQR';`
`$this->notification->initialize($config);`
`$this->notification->subject("Hello");`
`$this->notification->message("Hello i am adil");`
`$this->notification->sendMultiple(["fZP16uRHQCWfJ2j2_c6_P3:APA91bEbRzB3gexlOVYm1i1qyPGnfc8U02EoB9-v2F7XvbHiCGIk-ry-7Eoelwhlt4wRwRZgP722WhLzfoKIFmOFBLYi0FjYjP7-QdPr0Sx_HDuGG2jIlx-A2C_XiWHhV0FObPYd1qA0","fZP16uRHQCWfJ2j2_c6_P3:APA91bEbRzB3gexlOVYm1i1qyPGnfc8U02EoB9-v2F7XvbHiCGIk-ry-7Eoelwhlt4wRwRZgP722WhLzfoKIFmOFBLYi0FjYjP7-QdPr0Sx_HDuGG2jIlx-A2C_XiWHhV0FObPYd1qA0"]);``
