# Adobe Bridge Custom Metadata JSON GLAM Presets


Set of presets to read and write GLAM (Galleries, Libraries, Archives & Museums) metadata & others, for "Custom Metadata Panel for Bridge" [https://github.com/adobe-dmeservices/custom-metadata]


Currently the DC, ISAD(G), Photoshop, xmpRights & VRA Essential XMP presets are published and soon I hope to create presets for EAD, SPECTRUM & more.

Thanks a lot for your feedback !

---

## Notes


### **[default_view.json]**

This file is part of the 'Custom Metadata Panel for Bridge' Manual.

* Extension: https://exchange.adobe.com/creativecloud.details.103752.html
* User guide: https://github.com/adobe-dmeservices/custom-metadata/blob/master/User%20Guide.MD
* Overview video: https://youtu.be/_IoMGJiEHss

### **[core_properties_view.json]**
This file helps to make it easier to build a custom view, a JSON file containing commonly used properties could be included in the app config folder, in the app user manual, or in a shared custom views page. This would save time looking up namespace, prefix, and field type.


### **[Iptc4xmpCore_properties_view.json]**
IPTC Core schema 1.2

The namespace is "http://iptc.org/std/Iptc4xmpCore/1.0/xmlns/" and the preferred prefix is "Iptc4xmpCore".
Note that the IPTC Core schema also uses properties from the dc, xmpRights, and photoshop namespaces. This preset only contains Iptc4xmpCore properties.
Documentation of the complete IPTC Core standard can be found at https://www.iptc.org/std/photometadata/specification/IPTC-PhotoMetadata#iptc-core-schema-1-2-specifications

### **[dc_properties_view.json]**
Dublin Core Elements 1.1 Standard

Note that the XMP specification limits dc:format and dc:language to read-only.

The namespace is "http://purl.org/dc/elements/1.1/" and the preferred prefix is "dc".
Documentation of the complete Dubin Core standard can be found at https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#section-3

### **[isadg_properties_view.json]**
ISAD(G) 2000 Standard

The namespace is "https://gist.github.com/anarchivist/826364" and the preferred prefix is "isadg".
Documentation of the complete ISAD(G) Core standard can be found at https://www.ica.org/sites/default/files/CBPS_2000_Guidelines_ISAD%28G%29_Second-edition_EN.pdf_

### **[photoshop_properties_view.json]**
XMP properties in the Photoshop namespace

### **[vrae_properties_view.json]**
VRA Essential XMP is a simplified version of VRA Core using only the display properties and six user-defined custom properties. 

The namespace is "http://www.vraweb.org/vracore/4.0/essential/" and the preferred prefix is "vrae".
Documentation of the complete VRA Core standard can be found at http://www.loc.gov/standards/vracore/

### **[xmpRights_properties_view.json]**
.
